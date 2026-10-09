# Gemini — Setswana — API Evidence

**Source file:** `tsn_api_evidence.jsonl`  
**Records:** 5  
**Status:** Transcription of recorded API evidence; not a screenshot.

## Batch 1

**model:** `gemini-3.1-pro-preview`  
**language:** `tsn`  
**time_utc:** `2026-10-09T10:58:12+00:00`  
**batch_id:** `tsn-20261009T105812912058Z-1`  
**method:** `zero-shot`  
**prompt_sha256:** `f078677fbaaca182629a0bed0c41dbf5f597b2c1bc9253e348874b9f0d05c917`  

### Prompt

```text
Generate a batch of 20 sentiment-bearing words in Setswana.

For every candidate, provide:
1. the word in Setswana;
2. a concise English gloss;
3. a preliminary polarity: positive, negative, or neutral; and
4. a short explanation of its typical emotional meaning.

Requirements:
- Include only words genuinely used in Setswana.
- Do not invent, transliterate, or silently borrow words from another language.
- Exclude proper names, punctuation, and complete sentences.
- Exclude every item in the exclusion list below.
- The candidate should be a single lexical item (not a phrase).
- Produce at most 20 candidates. Do not sacrifice quality to meet the number.
- Use 'neutral' only when it is a defensible polarity category.
- Return only a valid JSON array of objects with keys: word, english_gloss, polarity, explanation.

Exclusion list: []

```


### Raw model response

```json
[{"word":"lorato","english_gloss":"love","polarity":"positive","explanation":"Expresses deep affection and care."},{"word":"boitumelo","english_gloss":"happiness","polarity":"positive","explanation":"Denotes a state of joy, gladness, or delight."},{"word":"kgalefo","english_gloss":"anger","polarity":"negative","explanation":"Refers to strong feelings of displeasure or rage."},{"word":"letlhoo","english_gloss":"hatred","polarity":"negative","explanation":"Expresses intense dislike or animosity towards someone or something."},{"word":"tsholofelo","english_gloss":"hope","polarity":"positive","explanation":"Conveys a feeling of expectation and desire for a certain thing to happen."},{"word":"kutlobotlhoko","english_gloss":"sadness","polarity":"negative","explanation":"Describes deep emotional pain, sorrow, or grief."},{"word":"bopelonomi","english_gloss":"kindness","polarity":"positive","explanation":"Represents a gentle, caring, and generous disposition."},{"word":"lefufa","english_gloss":"jealousy","polarity":"negative","explanation":"Denotes feelings of envy or resentment towards others."},{"word":"kagiso","english_gloss":"peace","polarity":"positive","explanation":"Refers to harmony, tranquility, and the absence of conflict."},{"word":"tshabo","english_gloss":"fear","polarity":"negative","explanation":"Expresses an unpleasant emotion caused by the belief that someone or something is dangerous."},{"word":"monate","english_gloss":"pleasantness","polarity":"positive","explanation":"Describes something that is nice, enjoyable, or tasteful."},{"word":"botshwakga","english_gloss":"laziness","polarity":"negative","explanation":"Refers to an unwillingness to work or use energy, generally viewed negatively."},{"word":"tlotlo","english_gloss":"respect","polarity":"positive","explanation":"Shows admiration and high regard for someone or something."},{"word":"lenyatso","english_gloss":"disrespect","polarity":"negative","explanation":"Conveys contempt, disdain, or a lack of respect."},{"word":"bopelotlhomogi","english_gloss":"compassion","polarity":"positive","explanation":"Expresses sympathy and concern for the sufferings or misfortunes of others."},{"word":"boferefere","english_gloss":"deceitfulness","polarity":"negative","explanation":"Refers to dishonesty, fraud, or trickery."},{"word":"tshepo","english_gloss":"trust","polarity":"positive","explanation":"Denotes firm belief in the reliability, truth, or ability of someone or something."},{"word":"boikgogomoso","english_gloss":"arrogance","polarity":"negative","explanation":"Describes an exaggerated sense of one's own importance or abilities."},{"word":"bopelokgale","english_gloss":"bravery","polarity":"positive","explanation":"Represents courage and the ability to face danger or pain without showing fear."},{"word":"makala","english_gloss":"surprise","polarity":"neutral","explanation":"Indicates astonishment or wonder, which can be either positive or negative depending on the context."}]
```

## Batch 2

**model:** `gemini-3.1-pro-preview`  
**language:** `tsn`  
**time_utc:** `2026-10-09T10:58:39+00:00`  
**batch_id:** `tsn-20261009T105839556720Z-2`  
**method:** `zero-shot`  
**prompt_sha256:** `d031ebd99c0ddcb2b1f83e8768eb9bb8ec6c3109153816d28fdde637a1521183`  

### Prompt

```text
Generate a batch of 20 sentiment-bearing words in Setswana.

For every candidate, provide:
1. the word in Setswana;
2. a concise English gloss;
3. a preliminary polarity: positive, negative, or neutral; and
4. a short explanation of its typical emotional meaning.

Requirements:
- Include only words genuinely used in Setswana.
- Do not invent, transliterate, or silently borrow words from another language.
- Exclude proper names, punctuation, and complete sentences.
- Exclude every item in the exclusion list below.
- The candidate should be a single lexical item (not a phrase).
- Produce at most 20 candidates. Do not sacrifice quality to meet the number.
- Use 'neutral' only when it is a defensible polarity category.
- Return only a valid JSON array of objects with keys: word, english_gloss, polarity, explanation.

Exclusion list: ["boferefere", "boikgogomoso", "boitumelo", "bopelokgale", "bopelonomi", "bopelotlhomogi", "botshwakga", "kagiso", "kgalefo", "kutlobotlhoko", "lefufa", "lenyatso", "letlhoo", "lorato", "makala", "monate", "tlotlo", "tshabo", "tshepo", "tsholofelo"]

```


### Raw model response

```json
[{"word":"molemo","english_gloss":"goodness","polarity":"positive","explanation":"Refers to goodness, usefulness, or medicine, conveying a highly positive and beneficial state."},{"word":"kgalalelo","english_gloss":"glory","polarity":"positive","explanation":"Means glory or splendor, often used to express high praise or divine beauty."},{"word":"tshegofatso","english_gloss":"blessing","polarity":"positive","explanation":"Refers to a blessing or grace, carrying a strong positive sentiment of receiving good fortune."},{"word":"tshiamo","english_gloss":"righteousness","polarity":"positive","explanation":"Denotes righteousness, fairness, or justice, representing moral goodness."},{"word":"boikobo","english_gloss":"humility","polarity":"positive","explanation":"Means humility or submissiveness, considered a highly positive virtue in Setswana culture."},{"word":"bopelotshweu","english_gloss":"kindness","polarity":"positive","explanation":"Literally translates to a white heart, signifying purity of heart, kindness, and generosity."},{"word":"sebe","english_gloss":"sin","polarity":"negative","explanation":"Refers to a sin or moral wrongdoing, carrying a strong negative and condemnatory sentiment."},{"word":"kgololesego","english_gloss":"freedom","polarity":"positive","explanation":"Means freedom or liberation, evoking feelings of relief, independence, and joy."},{"word":"kgotsofalo","english_gloss":"satisfaction","polarity":"positive","explanation":"Denotes contentment or satisfaction, reflecting a peaceful and happy state of mind."},{"word":"lehuma","english_gloss":"poverty","polarity":"negative","explanation":"Means poverty or extreme need, associated with suffering and hardship."},{"word":"bokowa","english_gloss":"weakness","polarity":"negative","explanation":"Refers to physical or emotional weakness, often carrying a sentiment of vulnerability or inadequacy."},{"word":"botlhale","english_gloss":"wisdom","polarity":"positive","explanation":"Means wisdom or intelligence, a trait that is highly valued and praised in the culture."},{"word":"bosilo","english_gloss":"foolishness","polarity":"negative","explanation":"Denotes stupidity or foolishness, used to express disapproval or frustration."},{"word":"tlhobogo","english_gloss":"despair","polarity":"negative","explanation":"Refers to hopelessness or giving up, conveying deep sadness and defeat."},{"word":"kgatelelo","english_gloss":"oppression","polarity":"negative","explanation":"Means oppression or suppression, associated with injustice and suffering."},{"word":"tlhompho","english_gloss":"respect","polarity":"positive","explanation":"Denotes respect or reverence, a foundational positive value in social relations."},{"word":"boikanyego","english_gloss":"faithfulness","polarity":"positive","explanation":"Means trustworthiness, loyalty, or faithfulness, indicating reliability and good character."},{"word":"kotsi","english_gloss":"danger","polarity":"negative","explanation":"Refers to danger, harm, or an accident, evoking fear and negative consequences."},{"word":"phenyo","english_gloss":"victory","polarity":"positive","explanation":"Means victory or triumph, associated with celebration and success."},{"word":"botlhoko","english_gloss":"pain","polarity":"negative","explanation":"Refers to pain, bitterness, or hurt, conveying physical or emotional suffering."}]
```

## Batch 3

**model:** `gemini-3.1-pro-preview`  
**language:** `tsn`  
**time_utc:** `2026-10-09T10:59:10+00:00`  
**batch_id:** `tsn-20261009T105910994454Z-3`  
**method:** `zero-shot`  
**prompt_sha256:** `125e624ab9e7cfbedb51e1f191770fd7369e2c481b808d6371157174ea7d2fd5`  

### Prompt

```text
Generate a batch of 20 sentiment-bearing words in Setswana.

For every candidate, provide:
1. the word in Setswana;
2. a concise English gloss;
3. a preliminary polarity: positive, negative, or neutral; and
4. a short explanation of its typical emotional meaning.

Requirements:
- Include only words genuinely used in Setswana.
- Do not invent, transliterate, or silently borrow words from another language.
- Exclude proper names, punctuation, and complete sentences.
- Exclude every item in the exclusion list below.
- The candidate should be a single lexical item (not a phrase).
- Produce at most 20 candidates. Do not sacrifice quality to meet the number.
- Use 'neutral' only when it is a defensible polarity category.
- Return only a valid JSON array of objects with keys: word, english_gloss, polarity, explanation.

Exclusion list: ["boferefere", "boikanyego", "boikgogomoso", "boikobo", "boitumelo", "bokowa", "bopelokgale", "bopelonomi", "bopelotlhomogi", "bopelotshweu", "bosilo", "botlhale", "botlhoko", "botshwakga", "kagiso", "kgalalelo", "kgalefo", "kgatelelo", "kgololesego", "kgotsofalo", "kotsi", "kutlobotlhoko", "lefufa", "lehuma", "lenyatso", "letlhoo", "lorato", "makala", "molemo", "monate", "phenyo", "sebe", "tlhobogo", "tlhompho", "tlotlo", "tshabo", "tshegofatso", "tshepo", "tshiamo", "tsholofelo"]

```


### Raw model response

```json
[{"word":"lesego","english_gloss":"luck","polarity":"positive","explanation":"Refers to good fortune or a blessing, evoking feelings of gratitude and happiness."},{"word":"lethabo","english_gloss":"joy","polarity":"positive","explanation":"Expresses deep happiness, delight, or rejoicing in favorable circumstances."},{"word":"tshwenyego","english_gloss":"anxiety","polarity":"negative","explanation":"Describes a state of worry, trouble, or mental distress about a situation."},{"word":"boitshoko","english_gloss":"endurance","polarity":"positive","explanation":"Signifies perseverance and patience in the face of difficulties, highly valued as a strong character trait."},{"word":"tumelo","english_gloss":"faith","polarity":"positive","explanation":"Means belief or faith, often associated with spiritual or personal trust and confidence."},{"word":"boboi","english_gloss":"cowardice","polarity":"negative","explanation":"Refers to a lack of bravery or timidity, generally viewed as a negative trait."},{"word":"tshakgalo","english_gloss":"rage","polarity":"negative","explanation":"Denotes intense anger, fury, or outrage, representing a highly volatile emotional state."},{"word":"letshogo","english_gloss":"fear","polarity":"negative","explanation":"Means fright, panic, or terror in response to a perceived threat or danger."},{"word":"kgotso","english_gloss":"peace","polarity":"positive","explanation":"Represents tranquility, harmony, and the absence of conflict."},{"word":"boitshwarelo","english_gloss":"forgiveness","polarity":"positive","explanation":"The act of pardoning someone, associated with healing, grace, and letting go of grudges."},{"word":"kgakgamalo","english_gloss":"amazement","polarity":"neutral","explanation":"A state of surprise or wonder that can be triggered by either positive or negative unexpected events."},{"word":"bokgabane","english_gloss":"excellence","polarity":"positive","explanation":"Denotes virtue, nobility, or outstanding good character, eliciting admiration."},{"word":"ditlhong","english_gloss":"shame","polarity":"negative","explanation":"Refers to feelings of embarrassment, shyness, or disgrace."},{"word":"pelotelele","english_gloss":"patience","polarity":"positive","explanation":"Literally meaning a long heart, it describes someone who is tolerant and slow to anger."},{"word":"pelompe","english_gloss":"malice","polarity":"negative","explanation":"Literally meaning an ugly heart, it refers to wickedness, cruelty, or ill will towards others."},{"word":"kgaratlho","english_gloss":"struggle","polarity":"negative","explanation":"Describes hardship, fighting, or striving through difficult and exhausting circumstances."},{"word":"tsietso","english_gloss":"deception","polarity":"negative","explanation":"Means fraud, cheating, or betrayal, causing feelings of distrust and hurt."},{"word":"maaka","english_gloss":"lies","polarity":"negative","explanation":"Refers to falsehoods or untruths, strongly associated with dishonesty and broken trust."},{"word":"ngongorego","english_gloss":"complaint","polarity":"negative","explanation":"An expression of dissatisfaction, grievance, or unhappiness with a particular situation."},{"word":"pako","english_gloss":"praise","polarity":"positive","explanation":"Words of commendation or worship, bringing about feelings of pride, honor, and joy."}]
```

## Batch 4

**model:** `gemini-3.1-pro-preview`  
**language:** `tsn`  
**time_utc:** `2026-10-09T10:59:45+00:00`  
**batch_id:** `tsn-20261009T105945554206Z-4`  
**method:** `zero-shot`  
**prompt_sha256:** `9b91970dab6bf37447405b4f37d70741958e938c095dbfdbb8ac9fe0d1fe5bbd`  

### Prompt

```text
Generate a batch of 20 sentiment-bearing words in Setswana.

For every candidate, provide:
1. the word in Setswana;
2. a concise English gloss;
3. a preliminary polarity: positive, negative, or neutral; and
4. a short explanation of its typical emotional meaning.

Requirements:
- Include only words genuinely used in Setswana.
- Do not invent, transliterate, or silently borrow words from another language.
- Exclude proper names, punctuation, and complete sentences.
- Exclude every item in the exclusion list below.
- The candidate should be a single lexical item (not a phrase).
- Produce at most 20 candidates. Do not sacrifice quality to meet the number.
- Use 'neutral' only when it is a defensible polarity category.
- Return only a valid JSON array of objects with keys: word, english_gloss, polarity, explanation.

Exclusion list: ["boboi", "boferefere", "boikanyego", "boikgogomoso", "boikobo", "boitshoko", "boitshwarelo", "boitumelo", "bokgabane", "bokowa", "bopelokgale", "bopelonomi", "bopelotlhomogi", "bopelotshweu", "bosilo", "botlhale", "botlhoko", "botshwakga", "ditlhong", "kagiso", "kgakgamalo", "kgalalelo", "kgalefo", "kgaratlho", "kgatelelo", "kgololesego", "kgotso", "kgotsofalo", "kotsi", "kutlobotlhoko", "lefufa", "lehuma", "lenyatso", "lesego", "lethabo", "letlhoo", "letshogo", "lorato", "maaka", "makala", "molemo", "monate", "ngongorego", "pako", "pelompe", "pelotelele", "phenyo", "sebe", "tlhobogo", "tlhompho", "tlotlo", "tshabo", "tshakgalo", "tshegofatso", "tshepo", "tshiamo", "tsholofelo", "tshwenyego", "tsietso", "tumelo"]

```


### Raw model response

```json
[{"word": "Nnete", "english_gloss": "Truth", "polarity": "positive", "explanation": "Represents honesty and reality, which are highly valued and carry a positive sentiment."}, {"word": "Mathata", "english_gloss": "Problems", "polarity": "negative", "explanation": "Refers to troubles, difficulties, or challenges that cause distress."}, {"word": "Tshenyo", "english_gloss": "Destruction", "polarity": "negative", "explanation": "Denotes damage, ruin, or corruption, carrying a strong negative emotional weight."}, {"word": "Thotloetso", "english_gloss": "Encouragement", "polarity": "positive", "explanation": "Means motivation or support, inspiring positive feelings and confidence."}, {"word": "Pabalesego", "english_gloss": "Safety", "polarity": "positive", "explanation": "Refers to security and protection from harm, evoking feelings of peace and comfort."}, {"word": "Tshebo", "english_gloss": "Gossip", "polarity": "negative", "explanation": "Involves backbiting or malicious talk about others, which is socially frowned upon."}, {"word": "Phodiso", "english_gloss": "Healing", "polarity": "positive", "explanation": "The process of recovery from illness or pain, bringing relief and happiness."}, {"word": "Tshwaragano", "english_gloss": "Solidarity", "polarity": "positive", "explanation": "Signifies unity, cooperation, and working together, which are celebrated community values."}, {"word": "Tatlhego", "english_gloss": "Loss", "polarity": "negative", "explanation": "Associated with losing something or someone valuable, causing grief and sadness."}, {"word": "Kgwetlho", "english_gloss": "Challenge", "polarity": "neutral", "explanation": "Can mean a difficult task or an opportunity to grow, depending on the context."}, {"word": "Sefifi", "english_gloss": "Bad luck", "polarity": "negative", "explanation": "Refers to misfortune, darkness, or a bad omen, bringing fear or despair."}, {"word": "Monyenyo", "english_gloss": "Smile", "polarity": "positive", "explanation": "An expression of joy, friendliness, and warmth."}, {"word": "Khumo", "english_gloss": "Wealth", "polarity": "positive", "explanation": "Represents abundance, riches, and prosperity, generally viewed favorably."}, {"word": "Phoso", "english_gloss": "Mistake", "polarity": "negative", "explanation": "An error or fault, usually associated with regret or negative consequences."}, {"word": "Kgalemo", "english_gloss": "Rebuke", "polarity": "negative", "explanation": "A reprimand or scolding, which evokes feelings of guilt or strict discipline."}, {"word": "Kgololo", "english_gloss": "Deliverance", "polarity": "positive", "explanation": "The act of being freed or rescued from hardship, bringing immense relief."}, {"word": "Tidimalo", "english_gloss": "Silence", "polarity": "neutral", "explanation": "Can represent peaceful quietness or an awkward lack of communication."}, {"word": "Tlhabologo", "english_gloss": "Development", "polarity": "positive", "explanation": "Refers to progress, civilization, and improvement of living standards."}, {"word": "Leshwe", "english_gloss": "Filth", "polarity": "negative", "explanation": "Means dirt or impurity, causing disgust or physical and moral revulsion."}, {"word": "Modumo", "english_gloss": "Noise", "polarity": "negative", "explanation": "Often refers to a disturbance, uproar, or unpleasant sound that causes irritation."}]
```

## Batch 5

**model:** `gemini-3.1-pro-preview`  
**language:** `tsn`  
**time_utc:** `2026-10-09T11:00:28+00:00`  
**batch_id:** `tsn-20261009T110028732084Z-5`  
**method:** `zero-shot`  
**prompt_sha256:** `39ee6a6587a10dde5d9ca84252f9822436ad2f89f404c9a0159c1a809743dac7`  

### Prompt

```text
Generate a batch of 20 sentiment-bearing words in Setswana.

For every candidate, provide:
1. the word in Setswana;
2. a concise English gloss;
3. a preliminary polarity: positive, negative, or neutral; and
4. a short explanation of its typical emotional meaning.

Requirements:
- Include only words genuinely used in Setswana.
- Do not invent, transliterate, or silently borrow words from another language.
- Exclude proper names, punctuation, and complete sentences.
- Exclude every item in the exclusion list below.
- The candidate should be a single lexical item (not a phrase).
- Produce at most 20 candidates. Do not sacrifice quality to meet the number.
- Use 'neutral' only when it is a defensible polarity category.
- Return only a valid JSON array of objects with keys: word, english_gloss, polarity, explanation.

Exclusion list: ["boboi", "boferefere", "boikanyego", "boikgogomoso", "boikobo", "boitshoko", "boitshwarelo", "boitumelo", "bokgabane", "bokowa", "bopelokgale", "bopelonomi", "bopelotlhomogi", "bopelotshweu", "bosilo", "botlhale", "botlhoko", "botshwakga", "ditlhong", "kagiso", "kgakgamalo", "kgalalelo", "kgalefo", "kgalemo", "kgaratlho", "kgatelelo", "kgololesego", "kgololo", "kgotso", "kgotsofalo", "kgwetlho", "khumo", "kotsi", "kutlobotlhoko", "lefufa", "lehuma", "lenyatso", "lesego", "leshwe", "lethabo", "letlhoo", "letshogo", "lorato", "maaka", "makala", "mathata", "modumo", "molemo", "monate", "monyenyo", "ngongorego", "nnete", "pabalesego", "pako", "pelompe", "pelotelele", "phenyo", "phodiso", "phoso", "sebe", "sefifi", "tatlhego", "thotloetso", "tidimalo", "tlhabologo", "tlhobogo", "tlhompho", "tlotlo", "tshabo", "tshakgalo", "tshebo", "tshegofatso", "tshenyo", "tshepo", "tshiamo", "tsholofelo", "tshwaragano", "tshwenyego", "tsietso", "tumelo"]

```


### Raw model response

```json
[
  {
    "word": "ipelo",
    "english_gloss": "joy",
    "polarity": "positive",
    "explanation": "Refers to a state of great happiness, celebration, or rejoicing."
  },
  {
    "word": "mabela",
    "english_gloss": "arrogance",
    "polarity": "negative",
    "explanation": "Describes an attitude of conceitedness, haughtiness, or unwarranted pride."
  },
  {
    "word": "boikgantsho",
    "english_gloss": "boastfulness",
    "polarity": "negative",
    "explanation": "Relates to showing off or bragging, often viewed negatively as excessive pride."
  },
  {
    "word": "bopelotshetlha",
    "english_gloss": "greed",
    "polarity": "negative",
    "explanation": "Literally 'yellow-heartedness', it denotes selfishness, greed, or a lack of generosity."
  },
  {
    "word": "kgomotso",
    "english_gloss": "comfort",
    "polarity": "positive",
    "explanation": "Means consolation or comfort, offering a sense of peace and support during distress."
  },
  {
    "word": "letlhogonolo",
    "english_gloss": "luck",
    "polarity": "positive",
    "explanation": "Associated with good fortune, blessings, and positive outcomes."
  },
  {
    "word": "bosenyi",
    "english_gloss": "destructiveness",
    "polarity": "negative",
    "explanation": "Refers to wicked, criminal, or destructive behavior that harms others or property."
  },
  {
    "word": "bopelontle",
    "english_gloss": "kind-heartedness",
    "polarity": "positive",
    "explanation": "Literally 'beautiful heart', it signifies kindness, benevolence, and good intentions."
  },
  {
    "word": "tshotlego",
    "english_gloss": "suffering",
    "polarity": "negative",
    "explanation": "Describes a state of hardship, misery, or severe distress."
  },
  {
    "word": "tlhokomelo",
    "english_gloss": "care",
    "polarity": "positive",
    "explanation": "Implies taking good care of someone or something, showing attentiveness and responsibility."
  },
  {
    "word": "kgotlhang",
    "english_gloss": "conflict",
    "polarity": "negative",
    "explanation": "Refers to a dispute, disagreement, or clash, carrying a tense and adversarial emotional tone."
  },
  {
    "word": "tebogo",
    "english_gloss": "gratitude",
    "polarity": "positive",
    "explanation": "Expresses thankfulness, appreciation, and positive acknowledgment of a good deed."
  },
  {
    "word": "bopelokhutshwane",
    "english_gloss": "short-temperedness",
    "polarity": "negative",
    "explanation": "Literally 'short heart', it describes impatience, irritability, and a tendency to anger quickly."
  },
  {
    "word": "kgaogano",
    "english_gloss": "separation",
    "polarity": "negative",
    "explanation": "Often carries a sad or disruptive connotation of being torn apart or divided."
  },
  {
    "word": "poifo",
    "english_gloss": "fear",
    "polarity": "negative",
    "explanation": "Denotes a feeling of dread, apprehension, or fright in the face of danger."
  },
  {
    "word": "kgakgamatso",
    "english_gloss": "miracle",
    "polarity": "positive",
    "explanation": "Describes an amazing, awe-inspiring, or miraculous event that brings positive surprise."
  },
  {
    "word": "maikutlo",
    "english_gloss": "emotions",
    "polarity": "neutral",
    "explanation": "A general term for feelings or opinions; its specific sentiment depends entirely on the context."
  },
  {
    "word": "boitshwaro",
    "english_gloss": "behavior",
    "polarity": "neutral",
    "explanation": "Refers to a person's conduct or demeanor, which can be either good or bad depending on modifiers."
  },
  {
    "word": "thuso",
    "english_gloss": "assistance",
    "polarity": "positive",
    "explanation": "Represents support, aid, or relief provided to someone in need."
  },
  {
    "word": "mokgosi",
    "english_gloss": "alarm",
    "polarity": "negative",
    "explanation": "A loud call or alarm signaling danger, distress, or an urgent need for intervention."
  }
]
```
