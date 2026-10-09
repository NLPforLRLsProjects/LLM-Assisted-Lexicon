# Raw Model Output Evidence

**Provider:** OpenAI  
**Returned model:** gpt-4.1-2025-04-14  
**Prompt ID:** CG-01  
**Access time:** 2026-10-09 09:08:34 UTC  
**Temperature:** 0.2  
**Exclusion list:** []  

## Prompt

```text
Generate a batch of sentiment-bearing words in Sesotho.

For every candidate, provide:
1. the word in Sesotho;
2. a concise English gloss;
3. a preliminary polarity: positive, negative, or neutral; and
4. a short explanation of its typical emotional meaning.

Requirements:
- Include only words genuinely used in Sesotho.
- Do not invent, transliterate, or silently borrow words from another language.
- Exclude proper names, punctuation, and complete sentences.
- Exclude every item in [].
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

## Raw model response

```json
[
  {
    "word": "thabo",
    "english_gloss": "joy",
    "preliminary_polarity": "positive",
    "explanation": "Expresses happiness or delight, often used to describe a state of gladness."
  },
  {
    "word": "lerato",
    "english_gloss": "love",
    "preliminary_polarity": "positive",
    "explanation": "Conveys affection or deep care for someone or something."
  },
  {
    "word": "pelo-e bohloko",
    "english_gloss": "sorrow",
    "preliminary_polarity": "negative",
    "explanation": "Describes a feeling of sadness or emotional pain."
  },
  {
    "word": "khalefo",
    "english_gloss": "anger",
    "preliminary_polarity": "negative",
    "explanation": "Refers to a strong feeling of displeasure or rage."
  },
  {
    "word": "tshepo",
    "english_gloss": "hope",
    "preliminary_polarity": "positive",
    "explanation": "Indicates optimism or expectation for something good."
  },
  {
    "word": "tšabo",
    "english_gloss": "fear",
    "preliminary_polarity": "negative",
    "explanation": "Represents a feeling of being afraid or anxious."
  },
  {
    "word": "khotso",
    "english_gloss": "peace",
    "preliminary_polarity": "positive",
    "explanation": "Signifies calmness, tranquility, or absence of conflict."
  },
  {
    "word": "boikakaso",
    "english_gloss": "pride",
    "preliminary_polarity": "positive",
    "explanation": "Describes a sense of satisfaction or self-respect."
  },
  {
    "word": "pelo-e-mpe",
    "english_gloss": "malice",
    "preliminary_polarity": "negative",
    "explanation": "Refers to ill will or the desire to harm others."
  },
  {
    "word": "khotsofalo",
    "english_gloss": "contentment",
    "preliminary_polarity": "positive",
    "explanation": "Expresses a state of satisfaction or being pleased."
  }
]
```
