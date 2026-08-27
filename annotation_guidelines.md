# Native-Speaker Annotation Guidelines

## Purpose

Three annotators independently evaluate lexical validity, spelling, gloss accuracy, polarity, and intensity. Annotation supports two distinct activities:

1. Human-feedback refinement of generated lexicon candidates.
2. Construction or verification of the held-out evaluation resource containing 1,000 samples per language.

The same record must not be used both to construct the lexicon and to evaluate it.

## Labels

- **Positive:** expresses favourable affect, approval, benefit, happiness, hope, or another positive orientation.
- **Negative:** expresses unfavourable affect, disapproval, harm, anger, fear, sadness, or another negative orientation.
- **Neutral:** does not conventionally express positive or negative sentiment in the evaluated use.
- **Context-dependent:** has multiple common senses or changes orientation according to context and cannot be assigned one reliable word-level polarity.

## Intensity

| Score | Interpretation |
|---:|---|
| 1 | Very weak or nearly neutral |
| 2 | Weak |
| 3 | Moderate |
| 4 | Strong |
| 5 | Very strong |

## Independent annotation procedure

Each annotator must:

1. Confirm whether the form is a genuine word in the stated language.
2. Check spelling and identify obvious language confusion or borrowing.
3. assess whether the English gloss captures the ordinary meaning.
4. Assign polarity and intensity without consulting another annotator.
5. Consider polysemy, negation, idioms, cultural use, and domain-specific meaning.
6. Recommend retention, revision, or rejection.
7. State a concise reason for uncertain or corrected judgements.

## Adjudication

After independent annotation, compare the three judgements. Retain agreed entries, apply agreed corrections, and adjudicate disagreements using the documented guidelines. Exclude or mark an entry as context-dependent when the disagreement cannot be resolved confidently.

Report agreement separately for categorical decisions such as validity and polarity and for ordinal intensity ratings. State the statistic used, its value, and the number of items on which it was calculated.

## Leakage control

Annotators must not copy held-out evaluation records into prompts, contextual examples, candidate-generation material, or refinement evidence. Preserve separate identifiers and files for construction and evaluation records.

