# Claude Opus 4.5 — Sesotho raw API evidence

**Model:** `claude-opus-4-5-20251101`  
**Language:** Sesotho (sot)  
**Run ID:** `20261009T140730Z`  
**Recorded batches:** 5  
**Generated entries in raw JSON:** 100 (not independently validated)  

This document formats the preserved raw API response records; the JSONL is the source of truth.

## Batch 1

**Timestamp UTC:** 2026-09-16T14:09:08.788344+00:00  
**Request ID:** msg_011Cfro7BEVEyx5GVCNSE34r  
**Stop reason:** end_turn  
**Usage:** `{"input_tokens": 290, "output_tokens": 1149}`

### Prompt

```text
Generate distinct sentiment-bearing WORDS in Sesotho (ISO 639-3: sot).
This experiment is for creating language-specific sentiment lexicons.
For each candidate, return: "word" (a genuine single lexical item in Sesotho), "english_gloss" (concise English translation), "polarity" (positive, negative, or neutral), and "explanation" (one short statement of contextual emotional meaning).
Rules:
- Use ONLY authentic Sesotho lexical items. Do NOT silently substitute vocabulary from related Sepedi, Sesotho, or Setswana languages; avoid code-switching, loanwords of uncertain status, invented forms, proper nouns, sentences, and punctuation-only strings.
- Polarity must be exactly one of positive, negative, neutral.
- Prefer a balanced mix of polarities where possible. Neutral must have a plausible lexically grounded role.
- Exclude all words (case-insensitive) in this exclusion list: []
- Return ONLY a valid JSON ARRAY of objects with EXACT keys word, english_gloss, polarity, explanation. No markdown.
- If fewer than 20 defensible words exist, return fewer rather than inventing entries.

```

### Raw model response

```json
[
  {
    "word": "thabo",
    "english_gloss": "joy",
    "polarity": "positive",
    "explanation": "Expresses a deep sense of happiness and emotional fulfillment in Sesotho culture."
  },
  {
    "word": "lerato",
    "english_gloss": "love",
    "polarity": "positive",
    "explanation": "Conveys affection, care, and deep emotional attachment between people."
  },
  {
    "word": "kgotso",
    "english_gloss": "peace",
    "polarity": "positive",
    "explanation": "Represents tranquility, harmony, and absence of conflict."
  },
  {
    "word": "bohloko",
    "english_gloss": "pain/sorrow",
    "polarity": "negative",
    "explanation": "Describes emotional or physical suffering and distress."
  },
  {
    "word": "letswalo",
    "english_gloss": "fear/anxiety",
    "polarity": "negative",
    "explanation": "Indicates a state of worry, apprehension, or dread."
  },
  {
    "word": "bohale",
    "english_gloss": "anger/fierceness",
    "polarity": "negative",
    "explanation": "Expresses intense displeasure or aggressive emotional state."
  },
  {
    "word": "mosa",
    "english_gloss": "kindness/grace",
    "polarity": "positive",
    "explanation": "Reflects generosity, compassion, and benevolent behavior toward others."
  },
  {
    "word": "maswabi",
    "english_gloss": "sadness/grief",
    "polarity": "negative",
    "explanation": "Denotes feelings of sorrow, mourning, or emotional heaviness."
  },
  {
    "word": "tshabo",
    "english_gloss": "terror/fright",
    "polarity": "negative",
    "explanation": "Indicates extreme fear or being terrified of something."
  },
  {
    "word": "boikemelo",
    "english_gloss": "self-reliance",
    "polarity": "positive",
    "explanation": "Represents independence and the ability to depend on oneself."
  },
  {
    "word": "tlhompho",
    "english_gloss": "respect",
    "polarity": "positive",
    "explanation": "Conveys honor, esteem, and high regard for others."
  },
  {
    "word": "nyatso",
    "english_gloss": "contempt/disdain",
    "polarity": "negative",
    "explanation": "Expresses disrespect, scorn, or looking down upon someone."
  },
  {
    "word": "tshepo",
    "english_gloss": "hope/trust",
    "polarity": "positive",
    "explanation": "Indicates optimistic expectation and confidence in outcomes."
  },
  {
    "word": "bodutu",
    "english_gloss": "loneliness/boredom",
    "polarity": "negative",
    "explanation": "Describes feelings of isolation, solitude, or tedium."
  },
  {
    "word": "teboho",
    "english_gloss": "gratitude/thanks",
    "polarity": "positive",
    "explanation": "Expresses appreciation and thankfulness for received kindness."
  },
  {
    "word": "monyaka",
    "english_gloss": "celebration/festivity",
    "polarity": "positive",
    "explanation": "Associated with joyful gatherings and happy occasions."
  },
  {
    "word": "lehloyo",
    "english_gloss": "hatred",
    "polarity": "negative",
    "explanation": "Represents intense dislike or animosity toward someone."
  },
  {
    "word": "bophelo",
    "english_gloss": "life",
    "polarity": "neutral",
    "explanation": "Refers to existence itself, carrying contextual emotional weight."
  },
  {
    "word": "bohlale",
    "english_gloss": "wisdom/intelligence",
    "polarity": "positive",
    "explanation": "Valued quality representing knowledge and sound judgment."
  },
  {
    "word": "dihlong",
    "english_gloss": "shame/embarrassment",
    "polarity": "negative",
    "explanation": "Indicates feelings of humiliation or disgrace."
  }
]
```

## Batch 2

**Timestamp UTC:** 2026-10-09T14:09:27.041131+00:00  
**Request ID:** msg_011Cfro8VKCzX8bZ1mjacxiZ  
**Stop reason:** end_turn  
**Usage:** `{"input_tokens": 388, "output_tokens": 1169}`

### Prompt

```text
Generate exactly 20 distinct sentiment-bearing WORDS in Sesotho (ISO 639-3: sot).
This experiment is for creating language-specific sentiment lexicons.
For each candidate return: "word" (a genuine single lexical item in Sesotho), "english_gloss" (concise English translation), "polarity" (positive, negative, or neutral), and "explanation" (one short statement of contextual emotional meaning).
Rules:
- Use ONLY authentic Sesotho lexical items. Do NOT silently substitute vocabulary from related Sepedi, Sesotho, or Setswana languages; avoid code-switching, loanwords of uncertain status, invented forms, proper nouns, sentences, and punctuation-only strings.
- Polarity must be exactly one of positive, negative, neutral.
- Prefer a balanced mix of polarities where possible. Neutral must have a plausible lexically grounded role.
- Exclude all words (case-insensitive) in this exclusion list: ["bodutu", "bohale", "bohlale", "bohloko", "boikemelo", "bophelo", "dihlong", "kgotso", "lehloyo", "lerato", "letswalo", "maswabi", "monyaka", "mosa", "nyatso", "teboho", "thabo", "tlhompho", "tshabo", "tshepo"]
- Return ONLY a valid JSON ARRAY of objects with EXACT keys word, english_gloss, polarity, explanation. No markdown.
- If fewer than 20 defensible words exist, return fewer rather than inventing entries.

```

### Raw model response

```json
[
  {
    "word": "thabelo",
    "english_gloss": "prayer/joy",
    "polarity": "positive",
    "explanation": "Expresses spiritual devotion and inner peace, carrying positive emotional connotations in Sesotho culture."
  },
  {
    "word": "kutlwelo",
    "english_gloss": "sympathy/compassion",
    "polarity": "positive",
    "explanation": "Conveys empathetic understanding and emotional support toward others."
  },
  {
    "word": "mahlomola",
    "english_gloss": "sorrow/grief",
    "polarity": "negative",
    "explanation": "Describes deep emotional pain and sadness experienced during hardship or loss."
  },
  {
    "word": "pelo",
    "english_gloss": "heart",
    "polarity": "neutral",
    "explanation": "Central to emotional expression in Sesotho, its sentiment depends on context and modifiers."
  },
  {
    "word": "mohau",
    "english_gloss": "mercy/grace",
    "polarity": "positive",
    "explanation": "Represents kindness, forgiveness, and compassionate treatment of others."
  },
  {
    "word": "kgalefo",
    "english_gloss": "anger/wrath",
    "polarity": "negative",
    "explanation": "Intense negative emotion expressing displeasure or rage."
  },
  {
    "word": "botswa",
    "english_gloss": "laziness",
    "polarity": "negative",
    "explanation": "Describes unwillingness to work, viewed negatively in communal Sesotho society."
  },
  {
    "word": "tshireletso",
    "english_gloss": "protection",
    "polarity": "positive",
    "explanation": "Implies safety, security, and caring guardianship."
  },
  {
    "word": "tlala",
    "english_gloss": "hunger",
    "polarity": "negative",
    "explanation": "Represents physical and emotional suffering from lack of food."
  },
  {
    "word": "boiketlo",
    "english_gloss": "comfort/ease",
    "polarity": "positive",
    "explanation": "State of physical and emotional relaxation and contentment."
  },
  {
    "word": "senya",
    "english_gloss": "destroy/spoil",
    "polarity": "negative",
    "explanation": "Action verb implying damage, ruin, or corruption."
  },
  {
    "word": "hlonepha",
    "english_gloss": "respect",
    "polarity": "positive",
    "explanation": "Fundamental value in Sesotho culture expressing honor and esteem."
  },
  {
    "word": "boiphihlelo",
    "english_gloss": "experience",
    "polarity": "neutral",
    "explanation": "Refers to lived experience, with sentiment varying by context."
  },
  {
    "word": "matshwenyeho",
    "english_gloss": "troubles/worries",
    "polarity": "negative",
    "explanation": "Describes burdensome concerns causing mental distress."
  },
  {
    "word": "thuso",
    "english_gloss": "help/assistance",
    "polarity": "positive",
    "explanation": "Represents supportive action and communal solidarity."
  },
  {
    "word": "lefufa",
    "english_gloss": "jealousy/envy",
    "polarity": "negative",
    "explanation": "Negative emotion of resentment toward others' possessions or success."
  },
  {
    "word": "khothatso",
    "english_gloss": "encouragement/consolation",
    "polarity": "positive",
    "explanation": "Emotional support given to uplift someone during difficulties."
  },
  {
    "word": "phetoho",
    "english_gloss": "change/transformation",
    "polarity": "neutral",
    "explanation": "Describes alteration or transition, with sentiment depending on outcome."
  },
  {
    "word": "bolotsana",
    "english_gloss": "deceit/trickery",
    "polarity": "negative",
    "explanation": "Dishonest behavior intended to mislead others."
  },
  {
    "word": "lesedi",
    "english_gloss": "light",
    "polarity": "positive",
    "explanation": "Metaphorically represents hope, enlightenment, and positivity."
  }
]
```

## Batch 3

**Timestamp UTC:** 2026-10-09T14:09:45.808267+00:00  
**Request ID:** msg_011Cfro9syViB2W5rgv7VEGh  
**Stop reason:** end_turn  
**Usage:** `{"input_tokens": 495, "output_tokens": 1123}`

### Prompt

```text
Generate exactly 20 distinct sentiment-bearing WORDS in Sesotho (ISO 639-3: sot).
This experiment is for creating language-specific sentiment lexicons.
For each candidate return: "word" (a genuine single lexical item in Sesotho), "english_gloss" (concise English translation), "polarity" (positive, negative, or neutral), and "explanation" (one short statement of contextual emotional meaning).
Rules:
- Use ONLY authentic Sesotho lexical items. Do NOT silently substitute vocabulary from related Sepedi, Sesotho, or Setswana languages; avoid code-switching, loanwords of uncertain status, invented forms, proper nouns, sentences, and punctuation-only strings.
- Polarity must be exactly one of positive, negative, neutral.
- Prefer a balanced mix of polarities where possible. Neutral must have a plausible lexically grounded role.
- Exclude all words (case-insensitive) in this exclusion list: ["bodutu", "bohale", "bohlale", "bohloko", "boikemelo", "boiketlo", "boiphihlelo", "bolotsana", "bophelo", "botswa", "dihlong", "hlonepha", "kgalefo", "kgotso", "khothatso", "kutlwelo", "lefufa", "lehloyo", "lerato", "lesedi", "letswalo", "mahlomola", "maswabi", "matshwenyeho", "mohau", "monyaka", "mosa", "nyatso", "pelo", "phetoho", "senya", "teboho", "thabelo", "thabo", "thuso", "tlala", "tlhompho", "tshabo", "tshepo", "tshireletso"]
- Return ONLY a valid JSON ARRAY of objects with EXACT keys word, english_gloss, polarity, explanation. No markdown.
- If fewer than 20 defensible words exist, return fewer rather than inventing entries.

```

### Raw model response

```json
[
  {
    "word": "thabisa",
    "english_gloss": "to make happy",
    "polarity": "positive",
    "explanation": "Expresses the act of bringing joy or pleasure to someone"
  },
  {
    "word": "rata",
    "english_gloss": "to love/like",
    "polarity": "positive",
    "explanation": "Conveys affection, fondness, or preference toward someone or something"
  },
  {
    "word": "hlompha",
    "english_gloss": "to respect",
    "polarity": "positive",
    "explanation": "Indicates showing honor and esteem toward others"
  },
  {
    "word": "tshosa",
    "english_gloss": "to frighten",
    "polarity": "negative",
    "explanation": "Describes causing fear or terror in someone"
  },
  {
    "word": "hloriswa",
    "english_gloss": "to be tormented",
    "polarity": "negative",
    "explanation": "Expresses being subjected to suffering or persecution"
  },
  {
    "word": "lla",
    "english_gloss": "to cry",
    "polarity": "negative",
    "explanation": "Indicates weeping or expressing grief and sadness"
  },
  {
    "word": "nyakalla",
    "english_gloss": "to be joyful",
    "polarity": "positive",
    "explanation": "Describes a state of exuberant happiness and celebration"
  },
  {
    "word": "halefa",
    "english_gloss": "to become angry",
    "polarity": "negative",
    "explanation": "Indicates the experience of anger or becoming enraged"
  },
  {
    "word": "kgathalla",
    "english_gloss": "to care about",
    "polarity": "positive",
    "explanation": "Expresses concern and interest in someone's wellbeing"
  },
  {
    "word": "tshwenyeha",
    "english_gloss": "to be worried",
    "polarity": "negative",
    "explanation": "Describes a state of anxiety or being troubled"
  },
  {
    "word": "leboha",
    "english_gloss": "to thank",
    "polarity": "positive",
    "explanation": "Expresses gratitude and appreciation toward someone"
  },
  {
    "word": "ikutlwa",
    "english_gloss": "to feel",
    "polarity": "neutral",
    "explanation": "Describes the general capacity to experience emotions or sensations"
  },
  {
    "word": "swaba",
    "english_gloss": "to be ashamed",
    "polarity": "negative",
    "explanation": "Indicates experiencing embarrassment or shame"
  },
  {
    "word": "kgotsofala",
    "english_gloss": "to be satisfied",
    "polarity": "positive",
    "explanation": "Expresses contentment and fulfillment"
  },
  {
    "word": "hlomoha",
    "english_gloss": "to be hurt emotionally",
    "polarity": "negative",
    "explanation": "Describes experiencing emotional pain or being offended"
  },
  {
    "word": "tsheha",
    "english_gloss": "to laugh",
    "polarity": "positive",
    "explanation": "Indicates expressing amusement and mirth"
  },
  {
    "word": "letsa",
    "english_gloss": "to cause to cry",
    "polarity": "negative",
    "explanation": "Describes making someone weep or feel sorrowful"
  },
  {
    "word": "makatsa",
    "english_gloss": "to amaze",
    "polarity": "neutral",
    "explanation": "Indicates causing wonder or astonishment which can be positive or negative"
  },
  {
    "word": "tshepahala",
    "english_gloss": "to be trustworthy",
    "polarity": "positive",
    "explanation": "Describes reliability and faithfulness in character"
  },
  {
    "word": "letswa",
    "english_gloss": "bitterness",
    "polarity": "negative",
    "explanation": "Refers to a harsh or unpleasant emotional state or taste"
  }
]
```

## Batch 4

**Timestamp UTC:** 2026-10-09T14:10:02.462643+00:00  
**Request ID:** msg_011CfroB6A1bGUPEUYivHc2Q  
**Stop reason:** end_turn  
**Usage:** `{"input_tokens": 600, "output_tokens": 1079}`

### Prompt

```text
Generate exactly 20 distinct sentiment-bearing WORDS in Sesotho (ISO 639-3: sot).
This experiment is for creating language-specific sentiment lexicons.
For each candidate return: "word" (a genuine single lexical item in Sesotho), "english_gloss" (concise English translation), "polarity" (positive, negative, or neutral), and "explanation" (one short statement of contextual emotional meaning).
Rules:
- Use ONLY authentic Sesotho lexical items. Do NOT silently substitute vocabulary from related Sepedi, Sesotho, or Setswana languages; avoid code-switching, loanwords of uncertain status, invented forms, proper nouns, sentences, and punctuation-only strings.
- Polarity must be exactly one of positive, negative, neutral.
- Prefer a balanced mix of polarities where possible. Neutral must have a plausible lexically grounded role.
- Exclude all words (case-insensitive) in this exclusion list: ["bodutu", "bohale", "bohlale", "bohloko", "boikemelo", "boiketlo", "boiphihlelo", "bolotsana", "bophelo", "botswa", "dihlong", "halefa", "hlomoha", "hlompha", "hlonepha", "hloriswa", "ikutlwa", "kgalefo", "kgathalla", "kgotso", "kgotsofala", "khothatso", "kutlwelo", "leboha", "lefufa", "lehloyo", "lerato", "lesedi", "letsa", "letswa", "letswalo", "lla", "mahlomola", "makatsa", "maswabi", "matshwenyeho", "mohau", "monyaka", "mosa", "nyakalla", "nyatso", "pelo", "phetoho", "rata", "senya", "swaba", "teboho", "thabelo", "thabisa", "thabo", "thuso", "tlala", "tlhompho", "tshabo", "tsheha", "tshepahala", "tshepo", "tshireletso", "tshosa", "tshwenyeha"]
- Return ONLY a valid JSON ARRAY of objects with EXACT keys word, english_gloss, polarity, explanation. No markdown.
- If fewer than 20 defensible words exist, return fewer rather than inventing entries.

```

### Raw model response

```json
[
  {
    "word": "thaba",
    "english_gloss": "be happy",
    "polarity": "positive",
    "explanation": "Expresses a state of joy or happiness in emotional contexts."
  },
  {
    "word": "fela",
    "english_gloss": "finish/end",
    "polarity": "neutral",
    "explanation": "Indicates completion which can carry emotional weight depending on context."
  },
  {
    "word": "tshaba",
    "english_gloss": "fear",
    "polarity": "negative",
    "explanation": "Describes the emotion of being afraid or running away from danger."
  },
  {
    "word": "hloya",
    "english_gloss": "hate",
    "polarity": "negative",
    "explanation": "Strong negative emotion expressing intense dislike or aversion."
  },
  {
    "word": "tshepa",
    "english_gloss": "trust",
    "polarity": "positive",
    "explanation": "Expresses confidence and reliance on someone or something."
  },
  {
    "word": "kgathatseha",
    "english_gloss": "be troubled",
    "polarity": "negative",
    "explanation": "Indicates a state of worry or disturbance."
  },
  {
    "word": "tshepisa",
    "english_gloss": "promise",
    "polarity": "positive",
    "explanation": "Conveys commitment and creates positive expectations."
  },
  {
    "word": "kena",
    "english_gloss": "enter",
    "polarity": "neutral",
    "explanation": "Action verb that can carry emotional significance in social contexts."
  },
  {
    "word": "phomola",
    "english_gloss": "rest",
    "polarity": "positive",
    "explanation": "Indicates relief and recuperation, bringing comfort."
  },
  {
    "word": "lwana",
    "english_gloss": "fight",
    "polarity": "negative",
    "explanation": "Describes conflict and aggression between parties."
  },
  {
    "word": "boloka",
    "english_gloss": "save/preserve",
    "polarity": "positive",
    "explanation": "Conveys protection and care for something valuable."
  },
  {
    "word": "lahla",
    "english_gloss": "throw away/abandon",
    "polarity": "negative",
    "explanation": "Indicates rejection or discarding, often with emotional pain."
  },
  {
    "word": "kholwa",
    "english_gloss": "believe",
    "polarity": "positive",
    "explanation": "Expresses faith and conviction in something or someone."
  },
  {
    "word": "shwa",
    "english_gloss": "die",
    "polarity": "negative",
    "explanation": "Represents death and associated grief and loss."
  },
  {
    "word": "pholoha",
    "english_gloss": "be saved/healed",
    "polarity": "positive",
    "explanation": "Indicates recovery and deliverance from harm."
  },
  {
    "word": "hloka",
    "english_gloss": "lack/need",
    "polarity": "negative",
    "explanation": "Expresses deficiency and the distress of wanting."
  },
  {
    "word": "fumana",
    "english_gloss": "find/obtain",
    "polarity": "positive",
    "explanation": "Conveys success and satisfaction in acquiring something."
  },
  {
    "word": "robala",
    "english_gloss": "sleep",
    "polarity": "neutral",
    "explanation": "Natural state that can imply peace or neglect contextually."
  },
  {
    "word": "sitwa",
    "english_gloss": "fail/be unable",
    "polarity": "negative",
    "explanation": "Indicates inability and associated frustration or disappointment."
  },
  {
    "word": "lokile",
    "english_gloss": "it is fine/okay",
    "polarity": "positive",
    "explanation": "Expression of satisfaction and acceptance of a situation."
  }
]
```

## Batch 5

**Timestamp UTC:** 2026-10-09T14:10:19.575540+00:00  
**Request ID:** msg_011CfroCMm9BHgj7a6pJ54xQ  
**Stop reason:** end_turn  
**Usage:** `{"input_tokens": 691, "output_tokens": 1170}`

### Prompt

```text
Generate exactly 20 distinct sentiment-bearing WORDS in Sesotho (ISO 639-3: sot).
This experiment is for creating language-specific sentiment lexicons.
For each candidate return: "word" (a genuine single lexical item in Sesotho), "english_gloss" (concise English translation), "polarity" (positive, negative, or neutral), and "explanation" (one short statement of contextual emotional meaning).
Rules:
- Use ONLY authentic Sesotho lexical items. Do NOT silently substitute vocabulary from related Sepedi, Sesotho, or Setswana languages; avoid code-switching, loanwords of uncertain status, invented forms, proper nouns, sentences, and punctuation-only strings.
- Polarity must be exactly one of positive, negative, neutral.
- Prefer a balanced mix of polarities where possible. Neutral must have a plausible lexically grounded role.
- Exclude all words (case-insensitive) in this exclusion list: ["bodutu", "bohale", "bohlale", "bohloko", "boikemelo", "boiketlo", "boiphihlelo", "boloka", "bolotsana", "bophelo", "botswa", "dihlong", "fela", "fumana", "halefa", "hloka", "hlomoha", "hlompha", "hlonepha", "hloriswa", "hloya", "ikutlwa", "kena", "kgalefo", "kgathalla", "kgathatseha", "kgotso", "kgotsofala", "kholwa", "khothatso", "kutlwelo", "lahla", "leboha", "lefufa", "lehloyo", "lerato", "lesedi", "letsa", "letswa", "letswalo", "lla", "lokile", "lwana", "mahlomola", "makatsa", "maswabi", "matshwenyeho", "mohau", "monyaka", "mosa", "nyakalla", "nyatso", "pelo", "phetoho", "pholoha", "phomola", "rata", "robala", "senya", "shwa", "sitwa", "swaba", "teboho", "thaba", "thabelo", "thabisa", "thabo", "thuso", "tlala", "tlhompho", "tshaba", "tshabo", "tsheha", "tshepa", "tshepahala", "tshepisa", "tshepo", "tshireletso", "tshosa", "tshwenyeha"]
- Return ONLY a valid JSON ARRAY of objects with EXACT keys word, english_gloss, polarity, explanation. No markdown.
- If fewer than 20 defensible words exist, return fewer rather than inventing entries.

```

### Raw model response

```json
[
  {
    "word": "thabela",
    "english_gloss": "rejoice for",
    "polarity": "positive",
    "explanation": "Expresses joy or happiness felt on behalf of someone or something."
  },
  {
    "word": "utlwisa",
    "english_gloss": "cause to feel/hurt",
    "polarity": "negative",
    "explanation": "Often used in context of causing emotional or physical pain to someone."
  },
  {
    "word": "kgothatsa",
    "english_gloss": "encourage",
    "polarity": "positive",
    "explanation": "Denotes the act of giving moral support or comfort to someone."
  },
  {
    "word": "hlonama",
    "english_gloss": "be offended",
    "polarity": "negative",
    "explanation": "Describes a state of feeling hurt or insulted by words or actions."
  },
  {
    "word": "tsietsi",
    "english_gloss": "trouble/distress",
    "polarity": "negative",
    "explanation": "Refers to a state of difficulty, hardship, or emotional distress."
  },
  {
    "word": "motlotlo",
    "english_gloss": "pride",
    "polarity": "positive",
    "explanation": "Expresses a sense of dignity and positive self-regard."
  },
  {
    "word": "ferekana",
    "english_gloss": "be confused/disturbed",
    "polarity": "negative",
    "explanation": "Indicates mental disturbance or emotional confusion."
  },
  {
    "word": "kgathala",
    "english_gloss": "be tired",
    "polarity": "negative",
    "explanation": "Describes physical or emotional exhaustion and weariness."
  },
  {
    "word": "tshohanyetsa",
    "english_gloss": "startle/frighten suddenly",
    "polarity": "negative",
    "explanation": "Refers to causing sudden fear or shock in someone."
  },
  {
    "word": "kgahlisa",
    "english_gloss": "please/delight",
    "polarity": "positive",
    "explanation": "Expresses the act of bringing pleasure or satisfaction to someone."
  },
  {
    "word": "matlafatsa",
    "english_gloss": "strengthen/empower",
    "polarity": "positive",
    "explanation": "Conveys giving strength or power, often emotionally uplifting."
  },
  {
    "word": "hlaola",
    "english_gloss": "choose/select",
    "polarity": "neutral",
    "explanation": "A deliberate act of selection without inherent positive or negative value."
  },
  {
    "word": "hlolwa",
    "english_gloss": "be defeated",
    "polarity": "negative",
    "explanation": "Indicates loss or failure, often carrying emotional disappointment."
  },
  {
    "word": "babatsa",
    "english_gloss": "praise/admire",
    "polarity": "positive",
    "explanation": "Expresses approval, admiration, or commendation toward someone."
  },
  {
    "word": "soaba",
    "english_gloss": "be ashamed/sad",
    "polarity": "negative",
    "explanation": "Denotes feelings of shame, regret, or sadness."
  },
  {
    "word": "tiisetsa",
    "english_gloss": "persevere/endure",
    "polarity": "positive",
    "explanation": "Conveys resilience and determination through difficult circumstances."
  },
  {
    "word": "kgaola",
    "english_gloss": "cut/sever",
    "polarity": "neutral",
    "explanation": "Physical action of cutting; sentiment depends on context."
  },
  {
    "word": "mahlonoko",
    "english_gloss": "pains/sorrows",
    "polarity": "negative",
    "explanation": "Refers to multiple instances of pain or deep suffering."
  },
  {
    "word": "pheha",
    "english_gloss": "cook/prepare",
    "polarity": "neutral",
    "explanation": "A domestic activity without inherent emotional valence."
  },
  {
    "word": "tshwarelo",
    "english_gloss": "forgiveness",
    "polarity": "positive",
    "explanation": "Represents the act of pardoning, bringing reconciliation and relief."
  }
]
```
