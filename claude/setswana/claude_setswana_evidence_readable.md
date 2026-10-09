# Claude — Setswana — API Evidence

**Source file:** `claude_tsn_evidence.jsonl`  
**Records:** 6  
**Status:** Transcription of recorded API evidence; not a screenshot.

## Batch 1

**provider:** `claude`  
**model:** `claude-opus-4-5-20251101`  
**language:** `Setswana`  
**language_code:** `tsn`  
**timestamp_utc:** `2026-09-16T14:10:39.123277+00:00`  
**run_id:** `20261009T140730Z`  
**batch:** `1`  

### Prompt

```text
Generate distinct sentiment-bearing WORDS in Setswana (ISO 639-3: tsn).
This experiment is for creating language-specific sentiment lexicons.
For each candidate, return: "word" (a genuine single lexical item in Setswana), "english_gloss" (concise English translation), "polarity" (positive, negative, or neutral), and "explanation" (one short statement of contextual emotional meaning).
Rules:
- Use ONLY authentic Setswana lexical items. Do NOT silently substitute vocabulary from related Sepedi, Sesotho, or Setswana languages; avoid code-switching, loanwords of uncertain status, invented forms, proper nouns, sentences, and punctuation-only strings.
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
    "word": "lorato",
    "english_gloss": "love",
    "polarity": "positive",
    "explanation": "Expresses deep affection and emotional connection between people."
  },
  {
    "word": "boitumelo",
    "english_gloss": "happiness",
    "polarity": "positive",
    "explanation": "Conveys a state of joy and contentment."
  },
  {
    "word": "kutlobotlhoko",
    "english_gloss": "sadness/pain",
    "polarity": "negative",
    "explanation": "Describes emotional suffering or heartache."
  },
  {
    "word": "bogale",
    "english_gloss": "anger/fierceness",
    "polarity": "negative",
    "explanation": "Indicates a state of being angry or fierce."
  },
  {
    "word": "poifo",
    "english_gloss": "fear",
    "polarity": "negative",
    "explanation": "Represents the emotion of being afraid or scared."
  },
  {
    "word": "kagiso",
    "english_gloss": "peace",
    "polarity": "positive",
    "explanation": "Signifies tranquility and absence of conflict."
  },
  {
    "word": "tlhomphego",
    "english_gloss": "respect",
    "polarity": "positive",
    "explanation": "Conveys admiration and regard for others."
  },
  {
    "word": "letshogo",
    "english_gloss": "shock/alarm",
    "polarity": "negative",
    "explanation": "Describes sudden fear or startled emotion."
  },
  {
    "word": "ditshego",
    "english_gloss": "laughter",
    "polarity": "positive",
    "explanation": "Associated with amusement and joyful expression."
  },
  {
    "word": "lehloyo",
    "english_gloss": "hatred",
    "polarity": "negative",
    "explanation": "Expresses intense dislike or animosity."
  },
  {
    "word": "kgotso",
    "english_gloss": "peace/greeting",
    "polarity": "positive",
    "explanation": "Used to wish peace and express goodwill."
  },
  {
    "word": "bosula",
    "english_gloss": "evil/badness",
    "polarity": "negative",
    "explanation": "Refers to wickedness or morally wrong behavior."
  },
  {
    "word": "botho",
    "english_gloss": "humanity/kindness",
    "polarity": "positive",
    "explanation": "Embodies compassion, dignity, and human kindness."
  },
  {
    "word": "dihlong",
    "english_gloss": "shame/embarrassment",
    "polarity": "negative",
    "explanation": "Describes feeling of disgrace or embarrassment."
  },
  {
    "word": "tsholofelo",
    "english_gloss": "hope",
    "polarity": "positive",
    "explanation": "Represents expectation and optimism for the future."
  },
  {
    "word": "tlala",
    "english_gloss": "hunger/famine",
    "polarity": "negative",
    "explanation": "Conveys physical suffering from lack of food."
  },
  {
    "word": "pelonomi",
    "english_gloss": "gentleness/mercy",
    "polarity": "positive",
    "explanation": "Describes a tender, merciful disposition."
  },
  {
    "word": "lefufa",
    "english_gloss": "jealousy/envy",
    "polarity": "negative",
    "explanation": "Indicates resentment toward others' advantages."
  },
  {
    "word": "boikokobetso",
    "english_gloss": "humility",
    "polarity": "neutral",
    "explanation": "Can be valued positively or seen as submissiveness depending on context."
  },
  {
    "word": "masetlapelo",
    "english_gloss": "suffering/misery",
    "polarity": "negative",
    "explanation": "Refers to prolonged hardship and emotional pain."
  }
]
```

### API metadata

```json
{
  "request_id": "msg_011CfroDo9trnygNP6wemiy3",
  "usage": {
    "input_tokens": 290,
    "output_tokens": 1101
  },
  "stop_reason": "end_turn"
}
```

## Batch 2

### Prompt

```text
Generate distinct sentiment-bearing WORDS in Setswana (ISO 639-3: tsn).
This experiment is for creating language-specific sentiment lexicons.
For each candidate return: "word" (a genuine single lexical item in Setswana), "english_gloss" (concise English translation), "polarity" (positive, negative, or neutral), and "explanation" (one short statement of contextual emotional meaning).
Rules:
- Use ONLY authentic Setswana lexical items. Do NOT silently substitute vocabulary from related Sepedi, Sesotho, or Setswana languages; avoid code-switching, loanwords of uncertain status, invented forms, proper nouns, sentences, and punctuation-only strings.
- Polarity must be exactly one of positive, negative, neutral.
- Prefer a balanced mix of polarities where possible. Neutral must have a plausible lexically grounded role.
- Exclude all words (case-insensitive) in this exclusion list: ["bogale", "boikokobetso", "boitumelo", "bosula", "botho", "dihlong", "ditshego", "kagiso", "kgotso", "kutlobotlhoko", "lefufa", "lehloyo", "letshogo", "lorato", "masetlapelo", "pelonomi", "poifo", "tlala", "tlhomphego", "tsholofelo"]
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
    "explanation": "Expresses a deep sense of happiness and emotional fulfillment."
  },
  {
    "word": "kgalefo",
    "english_gloss": "anger",
    "polarity": "negative",
    "explanation": "Denotes strong displeasure or rage towards someone or something."
  },
  {
    "word": "lefu",
    "english_gloss": "death",
    "polarity": "negative",
    "explanation": "Associated with grief, loss, and sorrow in most contexts."
  },
  {
    "word": "monate",
    "english_gloss": "pleasure",
    "polarity": "positive",
    "explanation": "Indicates enjoyment, delight, or a pleasant experience."
  },
  {
    "word": "botlhoko",
    "english_gloss": "pain",
    "polarity": "negative",
    "explanation": "Refers to physical or emotional suffering and distress."
  },
  {
    "word": "pelotshweu",
    "english_gloss": "kindness",
    "polarity": "positive",
    "explanation": "Describes a generous, warm-hearted disposition towards others."
  },
  {
    "word": "tlhobaelo",
    "english_gloss": "worry",
    "polarity": "negative",
    "explanation": "Expresses anxiety or concern about future events."
  },
  {
    "word": "kutlwelobotlhoko",
    "english_gloss": "compassion",
    "polarity": "positive",
    "explanation": "Feeling of sympathy and care for others' suffering."
  },
  {
    "word": "bogwera",
    "english_gloss": "friendship",
    "polarity": "positive",
    "explanation": "Represents the bond and mutual affection between friends."
  },
  {
    "word": "nyatso",
    "english_gloss": "criticism",
    "polarity": "negative",
    "explanation": "Involves disapproval or fault-finding towards someone."
  },
  {
    "word": "bopelotelele",
    "english_gloss": "patience",
    "polarity": "positive",
    "explanation": "The ability to endure difficulties calmly without complaint."
  },
  {
    "word": "bogodu",
    "english_gloss": "theft",
    "polarity": "negative",
    "explanation": "Associated with dishonesty and violation of trust."
  },
  {
    "word": "tshiamo",
    "english_gloss": "righteousness",
    "polarity": "positive",
    "explanation": "Moral correctness and adherence to ethical principles."
  },
  {
    "word": "maswabi",
    "english_gloss": "sadness",
    "polarity": "negative",
    "explanation": "Emotional state of unhappiness or sorrow."
  },
  {
    "word": "tlotlo",
    "english_gloss": "honour",
    "polarity": "positive",
    "explanation": "High respect and esteem given to someone worthy."
  },
  {
    "word": "bodutu",
    "english_gloss": "loneliness",
    "polarity": "negative",
    "explanation": "Feeling of isolation and emotional emptiness."
  },
  {
    "word": "tshepho",
    "english_gloss": "trust",
    "polarity": "positive",
    "explanation": "Confidence and reliance placed in someone's integrity."
  },
  {
    "word": "bokoa",
    "english_gloss": "weakness",
    "polarity": "neutral",
    "explanation": "Physical or moral lack of strength, contextually variable."
  },
  {
    "word": "boikgodiso",
    "english_gloss": "pride",
    "polarity": "neutral",
    "explanation": "Can be positive self-respect or negative arrogance depending on context."
  },
  {
    "word": "letlhoo",
    "english_gloss": "hatred",
    "polarity": "negative",
    "explanation": "Intense dislike or ill will towards someone."
  }
]
```

### API metadata

```json
{
  "request_id": "msg_011CfroF5ApuAavMTXYMKpGH",
  "usage": {
    "input_tokens": 395,
    "output_tokens": 1097
  },
  "stop_reason": "end_turn"
}
```

## Batch 3


### Raw model response

```json
[
  {
    "word": "itumela",
    "english_gloss": "to be happy",
    "polarity": "positive",
    "explanation": "Expresses a state of joy or contentment in emotional contexts."
  },
  {
    "word": "rata",
    "english_gloss": "to love/like",
    "polarity": "positive",
    "explanation": "Conveys affection or fondness toward someone or something."
  },
  {
    "word": "galefa",
    "english_gloss": "to be angry",
    "polarity": "negative",
    "explanation": "Indicates a state of anger or irritation."
  },
  {
    "word": "tshaba",
    "english_gloss": "to fear",
    "polarity": "negative",
    "explanation": "Expresses the emotion of being afraid or scared."
  },
  {
    "word": "hutsafala",
    "english_gloss": "to become sad",
    "polarity": "negative",
    "explanation": "Describes transitioning into a sorrowful emotional state."
  },
  {
    "word": "leboga",
    "english_gloss": "to thank",
    "polarity": "positive",
    "explanation": "Expresses gratitude and appreciation toward others."
  },
  {
    "word": "tlotla",
    "english_gloss": "to honor/respect",
    "polarity": "positive",
    "explanation": "Conveys showing reverence or high regard for someone."
  },
  {
    "word": "ila",
    "english_gloss": "to hate/detest",
    "polarity": "negative",
    "explanation": "Indicates strong aversion or dislike toward something."
  },
  {
    "word": "swaba",
    "english_gloss": "to be ashamed",
    "polarity": "negative",
    "explanation": "Expresses feelings of embarrassment or shame."
  },
  {
    "word": "kgatlhega",
    "english_gloss": "to be interested",
    "polarity": "positive",
    "explanation": "Shows curiosity or engagement with something appealing."
  },
  {
    "word": "botsalano",
    "english_gloss": "friendship",
    "polarity": "positive",
    "explanation": "Refers to the positive bond of companionship between people."
  },
  {
    "word": "tshwenyego",
    "english_gloss": "worry/trouble",
    "polarity": "negative",
    "explanation": "Describes a state of anxiety or being troubled."
  },
  {
    "word": "kgotsofala",
    "english_gloss": "to be satisfied",
    "polarity": "positive",
    "explanation": "Expresses contentment or fulfillment with a situation."
  },
  {
    "word": "ngongorega",
    "english_gloss": "to complain",
    "polarity": "negative",
    "explanation": "Indicates dissatisfaction expressed through grumbling."
  },
  {
    "word": "bofifi",
    "english_gloss": "darkness/gloom",
    "polarity": "negative",
    "explanation": "Metaphorically conveys sadness or hopelessness."
  },
  {
    "word": "tshepa",
    "english_gloss": "to trust",
    "polarity": "positive",
    "explanation": "Expresses confidence and faith in someone or something."
  },
  {
    "word": "sotlega",
    "english_gloss": "to suffer",
    "polarity": "negative",
    "explanation": "Describes enduring hardship or distress."
  },
  {
    "word": "itumelela",
    "english_gloss": "to rejoice for",
    "polarity": "positive",
    "explanation": "Expresses shared happiness or celebration for others."
  },
  {
    "word": "fela pelo",
    "english_gloss": "to lose heart",
    "polarity": "negative",
    "explanation": "Indicates becoming discouraged or losing hope."
  },
  {
    "word": "maitseo",
    "english_gloss": "good manners",
    "polarity": "positive",
    "explanation": "Refers to proper conduct that is socially valued and praised."
  }
]
```

### API metadata

```json
{
  "request_id": "msg_011CfroGGevBonA7zG8vi7B1",
  "usage": {
    "input_tokens": 507,
    "output_tokens": 1117
  },
  "stop_reason": "end_turn"
}
```

## Batch 4


### Raw model response

```json
[
  {
    "word": "ithaya",
    "english_gloss": "to be proud",
    "polarity": "positive",
    "explanation": "Expresses self-confidence and pride in one's achievements or identity."
  },
  {
    "word": "segakolodi",
    "english_gloss": "conscience",
    "polarity": "neutral",
    "explanation": "Refers to inner moral awareness, which can guide behavior in various emotional contexts."
  },
  {
    "word": "makgakga",
    "english_gloss": "enthusiasm",
    "polarity": "positive",
    "explanation": "Indicates eagerness and energetic excitement about something."
  },
  {
    "word": "tenwa",
    "english_gloss": "to be hated",
    "polarity": "negative",
    "explanation": "Describes the painful experience of being disliked or rejected by others."
  },
  {
    "word": "fela",
    "english_gloss": "to be finished/exhausted",
    "polarity": "negative",
    "explanation": "Conveys depletion, loss, or ending, often with emotional weight of finality."
  },
  {
    "word": "kgatlhisa",
    "english_gloss": "to impress/attract",
    "polarity": "positive",
    "explanation": "Describes causing admiration or interest in others."
  },
  {
    "word": "tlhoka",
    "english_gloss": "to lack/need",
    "polarity": "negative",
    "explanation": "Expresses deprivation or absence of something essential, evoking feelings of want."
  },
  {
    "word": "eletsa",
    "english_gloss": "to desire/wish",
    "polarity": "neutral",
    "explanation": "Indicates longing or aspiration, which can be positive or negative depending on context."
  },
  {
    "word": "gomotsa",
    "english_gloss": "to comfort/console",
    "polarity": "positive",
    "explanation": "Describes the act of soothing someone's emotional pain or distress."
  },
  {
    "word": "tlhodia",
    "english_gloss": "to startle/shock",
    "polarity": "negative",
    "explanation": "Conveys sudden fright or being taken aback unexpectedly."
  },
  {
    "word": "oketsa",
    "english_gloss": "to increase/add",
    "polarity": "positive",
    "explanation": "Implies growth, improvement, or enhancement of something valuable."
  },
  {
    "word": "nyenya",
    "english_gloss": "to despise/belittle",
    "polarity": "negative",
    "explanation": "Expresses contempt or looking down upon someone or something."
  },
  {
    "word": "tshwara",
    "english_gloss": "to hold/catch",
    "polarity": "neutral",
    "explanation": "Basic action verb that gains emotional meaning in contexts of support or capture."
  },
  {
    "word": "ineela",
    "english_gloss": "to surrender/dedicate",
    "polarity": "neutral",
    "explanation": "Describes giving oneself over, which can be positive devotion or negative defeat."
  },
  {
    "word": "bolaya",
    "english_gloss": "to kill",
    "polarity": "negative",
    "explanation": "Strongly negative term associated with death, violence, and destruction."
  },
  {
    "word": "golola",
    "english_gloss": "to liberate/free",
    "polarity": "positive",
    "explanation": "Expresses release from bondage or restriction, conveying relief and freedom."
  },
  {
    "word": "tshwenya",
    "english_gloss": "to bother/disturb",
    "polarity": "negative",
    "explanation": "Indicates causing annoyance, trouble, or emotional disturbance to someone."
  },
  {
    "word": "fitlhela",
    "english_gloss": "to find/discover",
    "polarity": "positive",
    "explanation": "Suggests successful attainment or discovery, often bringing satisfaction."
  },
  {
    "word": "latlhegelwa",
    "english_gloss": "to lose/be bereaved",
    "polarity": "negative",
    "explanation": "Expresses loss or bereavement, carrying deep emotional weight of grief."
  },
  {
    "word": "simolola",
    "english_gloss": "to begin/start",
    "polarity": "neutral",
    "explanation": "Marks initiation of something new, with emotional tone depending on context."
  }
]
```

### API metadata

```json
{
  "request_id": "msg_011CfroHVA2KkrFFEXyNfhYC",
  "usage": {
    "input_tokens": 606,
    "output_tokens": 1216
  },
  "stop_reason": "end_turn"
}
```

## Batch 5

### Prompt

```text
Generate distinct sentiment-bearing WORDS in Setswana (ISO 639-3: tsn).
This experiment is for creating language-specific sentiment lexicons.
For each candidate return: "word" (a genuine single lexical item in Setswana), "english_gloss" (concise English translation), "polarity" (positive, negative, or neutral), and "explanation" (one short statement of contextual emotional meaning).
Rules:
- Use ONLY authentic Setswana lexical items. Do NOT silently substitute vocabulary from related Sepedi, Sesotho, or Setswana languages; avoid code-switching, loanwords of uncertain status, invented forms, proper nouns, sentences, and punctuation-only strings.
- Polarity must be exactly one of positive, negative, neutral.
- Prefer a balanced mix of polarities where possible. Neutral must have a plausible lexically grounded role.
- Exclude all words (case-insensitive) in this exclusion list: ["bodutu", "bofifi", "bogale", "bogodu", "bogwera", "boikgodiso", "boikokobetso", "boitumelo", "bokoa", "bolaya", "bopelotelele", "bosula", "botho", "botlhoko", "botsalano", "dihlong", "ditshego", "eletsa", "fela", "fitlhela", "galefa", "golola", "gomotsa", "hutsafala", "ila", "ineela", "ithaya", "itumela", "itumelela", "kagiso", "kgalefo", "kgatlhega", "kgatlhisa", "kgotso", "kgotsofala", "kutlobotlhoko", "kutlwelobotlhoko", "latlhegelwa", "leboga", "lefu", "lefufa", "lehloyo", "letlhoo", "letshogo", "lorato", "maitseo", "makgakga", "masetlapelo", "maswabi", "monate", "ngongorega", "nyatso", "nyenya", "oketsa", "pelonomi", "pelotshweu", "poifo", "rata", "segakolodi", "simolola", "sotlega", "swaba", "tenwa", "thabo", "tlala", "tlhobaelo", "tlhodia", "tlhoka", "tlhomphego", "tlotla", "tlotlo", "tshaba", "tshepa", "tshepho", "tshiamo", "tsholofelo", "tshwara", "tshwenya", "tshwenyego"]
- Return ONLY a valid JSON ARRAY of objects with EXACT keys word, english_gloss, polarity, explanation. No markdown.
- If fewer than 20 defensible words exist, return fewer rather than inventing entries.

```


### Raw model response

```json
[
  {
    "word": "ipelela",
    "english_gloss": "rejoice",
    "polarity": "positive",
    "explanation": "Expresses a state of happiness and celebration."
  },
  {
    "word": "kgothatsa",
    "english_gloss": "encourage",
    "polarity": "positive",
    "explanation": "Conveys supportive and uplifting emotional action toward others."
  },
  {
    "word": "tlotlomatsa",
    "english_gloss": "honor/glorify",
    "polarity": "positive",
    "explanation": "Indicates showing high respect and admiration."
  },
  {
    "word": "utlwisa",
    "english_gloss": "cause to feel/hurt",
    "polarity": "negative",
    "explanation": "Often used in context of causing emotional or physical pain."
  },
  {
    "word": "seleka",
    "english_gloss": "mock",
    "polarity": "negative",
    "explanation": "Refers to ridiculing or making fun of someone in a hurtful way."
  },
  {
    "word": "tlotlega",
    "english_gloss": "be honored",
    "polarity": "positive",
    "explanation": "Describes the state of being respected or esteemed."
  },
  {
    "word": "makalo",
    "english_gloss": "surprise/amazement",
    "polarity": "neutral",
    "explanation": "Refers to astonishment which can be positive or negative depending on context."
  },
  {
    "word": "gobatsa",
    "english_gloss": "injure/harm",
    "polarity": "negative",
    "explanation": "Indicates causing physical or emotional damage to someone."
  },
  {
    "word": "baba",
    "english_gloss": "bitter/painful",
    "polarity": "negative",
    "explanation": "Describes something that causes emotional or physical discomfort."
  },
  {
    "word": "kopa",
    "english_gloss": "request/ask",
    "polarity": "neutral",
    "explanation": "A neutral act of making a request without inherent emotional charge."
  },
  {
    "word": "lapisa",
    "english_gloss": "tire/exhaust",
    "polarity": "negative",
    "explanation": "Refers to causing fatigue or weariness in someone."
  },
  {
    "word": "bopelontle",
    "english_gloss": "kindness/generosity",
    "polarity": "positive",
    "explanation": "Describes the quality of having a good and generous heart."
  },
  {
    "word": "sekisetsa",
    "english_gloss": "betray",
    "polarity": "negative",
    "explanation": "Indicates an act of disloyalty causing emotional harm."
  },
  {
    "word": "phuthologa",
    "english_gloss": "relax/be at ease",
    "polarity": "positive",
    "explanation": "Describes a comfortable and peaceful emotional state."
  },
  {
    "word": "fentse",
    "english_gloss": "defeated",
    "polarity": "negative",
    "explanation": "Refers to the state of being overcome, often bringing disappointment."
  },
  {
    "word": "tlhokomela",
    "english_gloss": "care for/look after",
    "polarity": "positive",
    "explanation": "Conveys nurturing attention and concern for wellbeing."
  },
  {
    "word": "gamarega",
    "english_gloss": "be astonished",
    "polarity": "neutral",
    "explanation": "A state of shock or surprise without inherent positive or negative value."
  },
  {
    "word": "tshosa",
    "english_gloss": "frighten",
    "polarity": "negative",
    "explanation": "Refers to causing fear or alarm in someone."
  },
  {
    "word": "ikanya",
    "english_gloss": "trust/have faith in",
    "polarity": "positive",
    "explanation": "Indicates placing confidence and belief in someone or something."
  },
  {
    "word": "tenego",
    "english_gloss": "annoyance/irritation",
    "polarity": "negative",
    "explanation": "Describes a state of being bothered or frustrated."
  }
]
```

### API metadata

```json
{
  "request_id": "msg_011CfroJyk2ANp5gCzt4BA6Q",
  "usage": {
    "input_tokens": 711,
    "output_tokens": 1144
  },
  "stop_reason": "end_turn"
}
```

## Batch 6
 

### Prompt

```text
Generate exactly distinct sentiment-bearing WORDS in Setswana (ISO 639-3: tsn).
This experiment is for creating language-specific sentiment lexicons.
For each candidate return: "word" (a genuine single lexical item in Setswana), "english_gloss" (concise English translation), "polarity" (positive, negative, or neutral), and "explanation" (one short statement of contextual emotional meaning).
Rules:
- Use ONLY authentic Setswana lexical items. Do NOT silently substitute vocabulary from related Sepedi, Sesotho, or Setswana languages; avoid code-switching, loanwords of uncertain status, invented forms, proper nouns, sentences, and punctuation-only strings.
- Polarity must be exactly one of positive, negative, neutral.
- Prefer a balanced mix of polarities where possible. Neutral must have a plausible lexically grounded role.
- Exclude all words (case-insensitive) in this exclusion list: ["baba", "bodutu", "bofifi", "bogale", "bogodu", "bogwera", "boikgodiso", "boikokobetso", "boitumelo", "bokoa", "bolaya", "bopelontle", "bopelotelele", "bosula", "botho", "botlhoko", "botsalano", "dihlong", "ditshego", "eletsa", "fela", "fentse", "fitlhela", "galefa", "gamarega", "gobatsa", "golola", "gomotsa", "hutsafala", "ikanya", "ila", "ineela", "ipelela", "ithaya", "itumela", "itumelela", "kagiso", "kgalefo", "kgatlhega", "kgatlhisa", "kgothatsa", "kgotso", "kgotsofala", "kopa", "kutlobotlhoko", "kutlwelobotlhoko", "lapisa", "latlhegelwa", "leboga", "lefu", "lefufa", "lehloyo", "letlhoo", "letshogo", "lorato", "maitseo", "makalo", "makgakga", "masetlapelo", "maswabi", "monate", "ngongorega", "nyatso", "nyenya", "oketsa", "pelonomi", "pelotshweu", "phuthologa", "poifo", "rata", "segakolodi", "sekisetsa", "seleka", "simolola", "sotlega", "swaba", "tenego", "tenwa", "thabo", "tlala", "tlhobaelo", "tlhodia", "tlhoka", "tlhokomela", "tlhomphego", "tlotla", "tlotlega", "tlotlo", "tlotlomatsa", "tshaba", "tshepa", "tshepho", "tshiamo", "tsholofelo", "tshosa", "tshwara", "tshwenya", "tshwenyego", "utlwisa"]
- Return ONLY a valid JSON ARRAY of objects with EXACT keys word, english_gloss, polarity, explanation. No markdown.
- If fewer than 1 defensible words exist, return fewer rather than inventing entries.

```


### Raw model response

```json
[{"word":"itumeleng","english_gloss":"rejoice","polarity":"positive","explanation":"An imperative verb form expressing joyful celebration or happiness, commonly used in encouraging contexts."}]
```

### API metadata

```json
{
  "request_id": "msg_011CfroLLmq7135o89xQZhU1",
  "usage": {
    "input_tokens": 815,
    "output_tokens": 48
  },
  "stop_reason": "end_turn"
}
```
