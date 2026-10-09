# Raw Model Output Evidence

**Provider:** OpenAI  
**Returned model:** gpt-4.1-2025-04-14  
**Prompt ID:** CG-01  
**Access time:** 2026-10-09 09:00:56 UTC  
**Temperature:** 0.2  
**Exclusion list:** []  

## Prompt

```text
Generate a batch of sentiment-bearing words in Setswana.

For every candidate, provide:
1. the word in Setswana;
2. a concise English gloss;
3. a preliminary polarity: positive, negative, or neutral; and
4. a short explanation of its typical emotional meaning.

Requirements:
- Include only words genuinely used in Setswana.
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
    "word": "lerato",
    "english_gloss": "love",
    "preliminary_polarity": "positive",
    "explanation": "Expresses affection, care, or deep fondness for someone or something."
  },
  {
    "word": "kutlo",
    "english_gloss": "compassion",
    "preliminary_polarity": "positive",
    "explanation": "Conveys empathy and understanding towards others' feelings or situations."
  },
  {
    "word": "kgatlego",
    "english_gloss": "happiness",
    "preliminary_polarity": "positive",
    "explanation": "Represents joy, satisfaction, or delight."
  },
  {
    "word": "pelo",
    "english_gloss": "heart (emotion)",
    "preliminary_polarity": "neutral",
    "explanation": "Refers to the seat of emotions, can be positive or negative depending on context."
  },
  {
    "word": "kutlobotlhoko",
    "english_gloss": "sadness",
    "preliminary_polarity": "negative",
    "explanation": "Describes a state of sorrow or unhappiness."
  },
  {
    "word": "kgalefo",
    "english_gloss": "anger",
    "preliminary_polarity": "negative",
    "explanation": "Indicates feelings of annoyance, displeasure, or rage."
  },
  {
    "word": "tshego",
    "english_gloss": "laughter",
    "preliminary_polarity": "positive",
    "explanation": "Associated with amusement, joy, or happiness."
  },
  {
    "word": "poifo",
    "english_gloss": "fear",
    "preliminary_polarity": "negative",
    "explanation": "Represents anxiety, worry, or being afraid."
  },
  {
    "word": "boitumelo",
    "english_gloss": "joy",
    "preliminary_polarity": "positive",
    "explanation": "Denotes great happiness or delight."
  },
  {
    "word": "kgatlhego",
    "english_gloss": "interest",
    "preliminary_polarity": "neutral",
    "explanation": "Shows curiosity or attention, can be positive or neutral depending on context."
  }
]
```
