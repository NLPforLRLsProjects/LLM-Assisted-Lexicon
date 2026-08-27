# Prompt Templates

These templates correspond to the LLM-assisted stages of the lexicon-construction framework. Replace values enclosed in angle brackets with the relevant experimental values. The held-out benchmark must never be inserted into these prompts.

## 1. System instruction

```text
You are a multilingual African-language lexicographic assistant. Work only with the target language specified by the user. Do not invent words, silently substitute a related language, or infer sentiment solely from an English translation. Follow the requested JSON schema exactly. When linguistic validity or polarity is uncertain, flag the item for human review.
```

## 2. Initial candidate generation

```text
Generate a batch of sentiment-bearing words in <LANGUAGE>.

For every candidate, provide:
1. the word in <LANGUAGE>;
2. a concise English gloss;
3. a preliminary polarity: positive, negative, or neutral; and
4. a short explanation of its typical emotional meaning.

Requirements:
- Include only words genuinely used in <LANGUAGE>.
- Do not invent, transliterate, or silently borrow words from another language.
- Exclude proper names, punctuation, and complete sentences.
- Exclude every item in <EXCLUSION_LIST>.
- Return only a valid JSON array.

Output format:
[
  {
    "word": "<TARGET_LANGUAGE_WORD>",
    "english_gloss": "<ENGLISH_GLOSS>",
    "preliminary_polarity": "positive|negative|neutral",
    "explanation": "<SHORT_EXPLANATION>"
  }
]
```

Run candidate generation in documented batches. Supply previously accepted and generated forms in `<EXCLUSION_LIST>` to reduce duplication.

## 3. Few-shot polarity and intensity assignment

```text
Evaluate the supplied <LANGUAGE> word. Verify its linguistic validity, English gloss, predominant sentiment polarity, and sentiment intensity.

Use one polarity label: positive, negative, or neutral.

Intensity scale:
1 = very weak or nearly neutral
2 = weak
3 = moderate
4 = strong
5 = very strong

Example input:
{"word": "thabo", "language": "Sepedi"}

Example output:
{
  "word": "thabo",
  "language": "Sepedi",
  "valid": true,
  "english_gloss": "happiness",
  "polarity": "positive",
  "intensity": 4,
  "justification": "The word normally expresses a strong positive emotional state."
}

Example input:
{"word": "kgalefo", "language": "Setswana"}

Example output:
{
  "word": "kgalefo",
  "language": "Setswana",
  "valid": true,
  "english_gloss": "anger",
  "polarity": "negative",
  "intensity": 4,
  "justification": "The word expresses a strong negative emotion."
}

Now evaluate:
{"word": "<CANDIDATE_WORD>", "language": "<LANGUAGE>"}

Return only one valid JSON object using the demonstrated fields.
```

## 4. Contextual sentence generation

```text
Target language: <LANGUAGE>
Target word: <CANDIDATE_WORD>
English gloss: <ENGLISH_GLOSS>
Preliminary polarity: <POLARITY>

Generate five natural sentences in <LANGUAGE> that use the target word in different contexts. Where linguistically appropriate, include an affirmative use, a negated use, an intensified use, a factual or weakly evaluative use, and an ambiguous use.

For every sentence, return:
- the sentence in <LANGUAGE>;
- an English translation;
- a sentence-level sentiment label;
- an intensity score from 1 to 5; and
- a short explanation.

Do not reproduce or paraphrase any held-out evaluation record. Do not assign a meaning that the target word cannot naturally carry. Return only a valid JSON array.
```

## 5. Contextual polarity analysis

```text
Analyse the sentiment expressed by the complete sentence.

Language: <LANGUAGE>
Target word: <CANDIDATE_WORD>
Sentence: <GENERATED_SENTENCE>
English translation: <ENGLISH_TRANSLATION>

Return:
{
  "sentiment": "positive|negative|neutral",
  "intensity": 1,
  "negation_present": false,
  "target_word_sense": "<MEANING_IN_THIS_CONTEXT>",
  "explanation": "<CONCISE_CONTEXTUAL_JUSTIFICATION>"
}

Consider negation, intensifiers, surrounding words, and compositional meaning. Do not infer sentence-level sentiment from the isolated target word alone. Return only valid JSON.
```

## 6. Automated candidate refinement

```text
Validate the following candidate for a <LANGUAGE> sentiment lexicon.

Candidate:
<CANDIDATE_JSON>

Contextual evaluations:
<CONTEXTUAL_EVALUATIONS>

Independent model evaluations:
<MULTI_MODEL_EVALUATIONS>

Select one decision: retain, revise, human_review, or reject.

Criteria:
1. The word must be linguistically valid in <LANGUAGE>.
2. The English gloss must match its ordinary meaning.
3. The polarity and intensity must be supported by contextual evidence.
4. Sense-dependent or unstable polarity must be flagged for human review.
5. Invented forms, incorrect-language forms, and proper names must be rejected.
6. The held-out benchmark must not inform this decision.

Return only:
{
  "word": "<WORD>",
  "decision": "retain|revise|human_review|reject",
  "final_gloss": "<GLOSS_OR_NULL>",
  "final_polarity": "positive|negative|neutral|context_dependent",
  "final_intensity": 1,
  "confidence": 0.0,
  "reason": "<CONCISE_JUSTIFICATION>"
}
```

## 7. Human-feedback refinement instruction

This is an annotation instruction, not an instruction for an LLM.

```text
Independently assess the proposed <LANGUAGE> lexicon entry without consulting the other annotators.

Candidate word: <CANDIDATE_WORD>
Proposed English gloss: <ENGLISH_GLOSS>
Proposed polarity: <POLARITY>
Proposed intensity: <INTENSITY>
Contextual examples: <EXAMPLE_SENTENCES>

Record:
1. Is it a valid <LANGUAGE> word? yes/no/uncertain
2. Is the spelling correct? yes/no
3. Is the English gloss accurate? yes/no/partially
4. What is the most appropriate polarity? positive/negative/neutral/context-dependent
5. What intensity should be assigned from 1 to 5?
6. Does another common sense change its polarity? yes/no
7. Should the entry be retained, revised, or rejected?
8. State the reason and any correction required.

Judge the natural, cultural, and contextual use of the word rather than relying only on its English translation.
```

## 8. Final output structure

Validated entries must conform to `schemas/lexicon_entry.schema.json`. Human judgements must conform to `schemas/human_annotation.schema.json`.

