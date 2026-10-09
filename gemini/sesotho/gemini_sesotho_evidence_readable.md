# Gemini — Sesotho — API Evidence

**Source file:** `sot_api_evidence.jsonl`  
**Records:** 5  
**Status:** Transcription of recorded API evidence; not a screenshot.

## Batch 1

**model:** `gemini-3.1-pro-preview`  
**language:** `sot`  
**time_utc:** `2026-10-09T10:55:09+00:00`  
**batch_id:** `sot-20261009T105509990405Z-1`  
**method:** `zero-shot`  
**prompt_sha256:** `6beb56ca6751dc4debc6c2eaccbba1c0dba2324e9703acce3036810e86b22f33`  

### Prompt

```text
Generate a batch of 20 sentiment-bearing words in Sesotho.

For every candidate, provide:
1. the word in Sesotho;
2. a concise English gloss;
3. a preliminary polarity: positive, negative, or neutral; and
4. a short explanation of its typical emotional meaning.

Requirements:
- Include only words genuinely used in Sesotho.
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
[{"word":"thabo","english_gloss":"joy","polarity":"positive","explanation":"Expresses a feeling of happiness or delight."},{"word":"lerato","english_gloss":"love","polarity":"positive","explanation":"Denotes deep affection and care for someone or something."},{"word":"bohloko","english_gloss":"pain","polarity":"negative","explanation":"Refers to physical or emotional suffering and distress."},{"word":"kgotso","english_gloss":"peace","polarity":"positive","explanation":"Represents tranquility, harmony, and absence of conflict."},{"word":"lehloeo","english_gloss":"hatred","polarity":"negative","explanation":"Indicates intense dislike or ill will towards others."},{"word":"maswabi","english_gloss":"sadness","polarity":"negative","explanation":"Conveys feelings of sorrow, disappointment, or regret."},{"word":"monate","english_gloss":"pleasant","polarity":"positive","explanation":"Describes something enjoyable, tasty, or feeling good."},{"word":"molemo","english_gloss":"goodness","polarity":"positive","explanation":"Refers to moral virtue, benefit, or kindness."},{"word":"kotsi","english_gloss":"danger","polarity":"negative","explanation":"Associated with harm, risk, or a perilous situation."},{"word":"hlompho","english_gloss":"respect","polarity":"positive","explanation":"Shows admiration and high regard for someone."},{"word":"tshabo","english_gloss":"fear","polarity":"negative","explanation":"Expresses anxiety or dread regarding a perceived threat."},{"word":"tshepo","english_gloss":"hope","polarity":"positive","explanation":"Indicates optimism and positive expectation for the future."},{"word":"lonya","english_gloss":"malice","polarity":"negative","explanation":"Represents cruelty, spitefulness, or a desire to cause harm."},{"word":"katleho","english_gloss":"success","polarity":"positive","explanation":"Denotes achievement, prosperity, and positive outcomes."},{"word":"musa","english_gloss":"kindness","polarity":"positive","explanation":"Refers to grace, mercy, and a gentle disposition."},{"word":"bohale","english_gloss":"anger","polarity":"negative","explanation":"Conveys wrath, fierceness, or a strong feeling of annoyance."},{"word":"mabe","english_gloss":"badness","polarity":"negative","explanation":"Describes something evil, ugly, or morally wrong."},{"word":"makala","english_gloss":"surprise","polarity":"neutral","explanation":"Expresses astonishment or wonder, which can be triggered by either positive or negative events."},{"word":"sebe","english_gloss":"sin","polarity":"negative","explanation":"Refers to a moral transgression or wrongdoing."},{"word":"kgathatso","english_gloss":"trouble","polarity":"negative","explanation":"Indicates worry, bother, or a source of distress."}]
```

## Batch 2

**model:** `gemini-3.1-pro-preview`  
**language:** `sot`  
**time_utc:** `2026-10-09T10:55:49+00:00`  
**batch_id:** `sot-20261009T105549266592Z-2`  
**method:** `zero-shot`  
**prompt_sha256:** `93b449b875bb85cf91bd4e44c2c800917ba4548b629d66ad75bc4a379de2ba20`  

### Prompt

```text
Generate a batch of 20 sentiment-bearing words in Sesotho.

For every candidate, provide:
1. the word in Sesotho;
2. a concise English gloss;
3. a preliminary polarity: positive, negative, or neutral; and
4. a short explanation of its typical emotional meaning.

Requirements:
- Include only words genuinely used in Sesotho.
- Do not invent, transliterate, or silently borrow words from another language.
- Exclude proper names, punctuation, and complete sentences.
- Exclude every item in the exclusion list below.
- The candidate should be a single lexical item (not a phrase).
- Produce at most 20 candidates. Do not sacrifice quality to meet the number.
- Use 'neutral' only when it is a defensible polarity category.
- Return only a valid JSON array of objects with keys: word, english_gloss, polarity, explanation.

Exclusion list: ["bohale", "bohloko", "hlompho", "katleho", "kgathatso", "kgotso", "kotsi", "lehloeo", "lerato", "lonya", "mabe", "makala", "maswabi", "molemo", "monate", "musa", "sebe", "thabo", "tshabo", "tshepo"]

```


### Raw model response

```json
[{"word": "kgotsofalo", "english_gloss": "satisfaction", "polarity": "positive", "explanation": "Indicates a state of contentment or being satisfied."}, {"word": "kgalefo", "english_gloss": "anger", "polarity": "negative", "explanation": "Refers to intense anger or wrath."}, {"word": "monyaka", "english_gloss": "joy", "polarity": "positive", "explanation": "Expresses a deep sense of enjoyment, excitement, or pleasure."}, {"word": "leshano", "english_gloss": "lie", "polarity": "negative", "explanation": "Represents deceit or telling lies, carrying a strong negative connotation."}, {"word": "kananelo", "english_gloss": "appreciation", "polarity": "positive", "explanation": "Expresses gratitude, approval, or appreciation for something."}, {"word": "qenehelo", "english_gloss": "compassion", "polarity": "positive", "explanation": "Refers to feeling sympathy or compassion towards someone's plight."}, {"word": "mohau", "english_gloss": "mercy", "polarity": "positive", "explanation": "Denotes kindness, mercy, or grace shown to others."}, {"word": "kgalalelo", "english_gloss": "glory", "polarity": "positive", "explanation": "Associated with majesty, splendor, and high honor."}, {"word": "thohako", "english_gloss": "curse", "polarity": "negative", "explanation": "Represents a curse or malediction, conveying strong ill will."}, {"word": "tshwarelo", "english_gloss": "forgiveness", "polarity": "positive", "explanation": "The act of pardoning or forgiving, bringing emotional relief."}, {"word": "bofuma", "english_gloss": "poverty", "polarity": "negative", "explanation": "Refers to destitution or extreme poverty, inducing feelings of hardship."}, {"word": "hlonama", "english_gloss": "sadness", "polarity": "negative", "explanation": "Describes a state of being gloomy, sulky, or sad."}, {"word": "nyediso", "english_gloss": "contempt", "polarity": "negative", "explanation": "Indicates disdain, scorn, or looking down upon someone."}, {"word": "tshotleho", "english_gloss": "suffering", "polarity": "negative", "explanation": "Refers to severe hardship, suffering, or misery."}, {"word": "kamohelo", "english_gloss": "acceptance", "polarity": "positive", "explanation": "Expresses a welcoming attitude, acceptance, or hospitality."}, {"word": "bohlale", "english_gloss": "wisdom", "polarity": "positive", "explanation": "Denotes intelligence, wisdom, and good judgment, highly valued emotionally."}, {"word": "lehlohonolo", "english_gloss": "blessing", "polarity": "positive", "explanation": "Represents good fortune, luck, or a blessing."}, {"word": "sefifi", "english_gloss": "misfortune", "polarity": "negative", "explanation": "Refers to bad luck, darkness, or a state of mourning."}, {"word": "kgesa", "english_gloss": "scorn", "polarity": "negative", "explanation": "The act of despising, rejecting, or treating with contempt."}, {"word": "ntle", "english_gloss": "beautiful", "polarity": "positive", "explanation": "Describes something beautiful, good, or aesthetically pleasing."}]
```

## Batch 3

**model:** `gemini-3.1-pro-preview`  
**language:** `sot`  
**time_utc:** `2026-10-09T10:56:22+00:00`  
**batch_id:** `sot-20261009T105622038753Z-3`  
**method:** `zero-shot`  
**prompt_sha256:** `845a97ab6113420deceaca7be60a21cfca63906bb9afb9ce64cfe93f48638df1`  

### Prompt

```text
Generate a batch of 20 sentiment-bearing words in Sesotho.

For every candidate, provide:
1. the word in Sesotho;
2. a concise English gloss;
3. a preliminary polarity: positive, negative, or neutral; and
4. a short explanation of its typical emotional meaning.

Requirements:
- Include only words genuinely used in Sesotho.
- Do not invent, transliterate, or silently borrow words from another language.
- Exclude proper names, punctuation, and complete sentences.
- Exclude every item in the exclusion list below.
- The candidate should be a single lexical item (not a phrase).
- Produce at most 20 candidates. Do not sacrifice quality to meet the number.
- Use 'neutral' only when it is a defensible polarity category.
- Return only a valid JSON array of objects with keys: word, english_gloss, polarity, explanation.

Exclusion list: ["bofuma", "bohale", "bohlale", "bohloko", "hlompho", "hlonama", "kamohelo", "kananelo", "katleho", "kgalalelo", "kgalefo", "kgathatso", "kgesa", "kgotso", "kgotsofalo", "kotsi", "lehloeo", "lehlohonolo", "lerato", "leshano", "lonya", "mabe", "makala", "maswabi", "mohau", "molemo", "monate", "monyaka", "musa", "ntle", "nyediso", "qenehelo", "sebe", "sefifi", "thabo", "thohako", "tshabo", "tshepo", "tshotleho", "tshwarelo"]

```


### Raw model response

```json
[{"word":"tlotla","english_gloss":"honor","polarity":"positive","explanation":"Expresses high respect, prestige, or glory given to someone."},{"word":"nyahama","english_gloss":"despair","polarity":"negative","explanation":"Denotes a loss of hope, discouragement, or emotional giving up."},{"word":"tshwenyeho","english_gloss":"anxiety","polarity":"negative","explanation":"Indicates mental distress, worry, or a state of being troubled."},{"word":"babatsa","english_gloss":"admire","polarity":"positive","explanation":"Expresses strong approval, praise, or amazement at something good."},{"word":"thetso","english_gloss":"deception","polarity":"negative","explanation":"Denotes trickery or fraud, eliciting feelings of betrayal."},{"word":"tshediso","english_gloss":"comfort","polarity":"positive","explanation":"Brings relief, solace, or emotional support during hard times."},{"word":"tokoloho","english_gloss":"freedom","polarity":"positive","explanation":"Represents liberation, autonomy, and the removal of oppression."},{"word":"tshehetso","english_gloss":"support","polarity":"positive","explanation":"Denotes helpfulness, backing, and solidarity with others."},{"word":"bopelonomi","english_gloss":"kindness","polarity":"positive","explanation":"Characterized by a good, generous, and compassionate heart."},{"word":"mona","english_gloss":"jealousy","polarity":"negative","explanation":"Represents resentment or envy towards the success of others."},{"word":"bokhopo","english_gloss":"wickedness","polarity":"negative","explanation":"Indicates cruel intent, malice, or evil behavior."},{"word":"bobe","english_gloss":"evil","polarity":"negative","explanation":"A fundamental term for immorality, badness, or harm."},{"word":"sebete","english_gloss":"courage","polarity":"positive","explanation":"Represents fearlessness, bravery, and strength of character."},{"word":"kgotlello","english_gloss":"perseverance","polarity":"positive","explanation":"Shows resilience, endurance, and patience in the face of hardship."},{"word":"nyefolo","english_gloss":"insult","polarity":"negative","explanation":"Expresses deep disrespect, derogation, or verbal abuse."},{"word":"tlhekefetso","english_gloss":"abuse","polarity":"negative","explanation":"Denotes severe mistreatment, harassment, or violation of rights."},{"word":"thabisa","english_gloss":"delight","polarity":"positive","explanation":"The act of making someone happy, pleased, or joyful."},{"word":"nyatsa","english_gloss":"criticize","polarity":"negative","explanation":"Expresses disapproval, condemnation, or fault-finding."},{"word":"hloya","english_gloss":"hate","polarity":"negative","explanation":"A strong verb indicating intense dislike or animosity."},{"word":"rata","english_gloss":"love","polarity":"positive","explanation":"The verb form for expressing deep affection, care, or preference."}]
```

## Batch 4

**model:** `gemini-3.1-pro-preview`  
**language:** `sot`  
**time_utc:** `2026-10-09T10:57:00+00:00`  
**batch_id:** `sot-20261009T105700614059Z-4`  
**method:** `zero-shot`  
**prompt_sha256:** `0080f26915273f76aa7ac8ad3a063537dc306b95da301f38535e4e9f999aa92a`  

### Prompt

```text
Generate a batch of 20 sentiment-bearing words in Sesotho.

For every candidate, provide:
1. the word in Sesotho;
2. a concise English gloss;
3. a preliminary polarity: positive, negative, or neutral; and
4. a short explanation of its typical emotional meaning.

Requirements:
- Include only words genuinely used in Sesotho.
- Do not invent, transliterate, or silently borrow words from another language.
- Exclude proper names, punctuation, and complete sentences.
- Exclude every item in the exclusion list below.
- The candidate should be a single lexical item (not a phrase).
- Produce at most 20 candidates. Do not sacrifice quality to meet the number.
- Use 'neutral' only when it is a defensible polarity category.
- Return only a valid JSON array of objects with keys: word, english_gloss, polarity, explanation.

Exclusion list: ["babatsa", "bobe", "bofuma", "bohale", "bohlale", "bohloko", "bokhopo", "bopelonomi", "hlompho", "hlonama", "hloya", "kamohelo", "kananelo", "katleho", "kgalalelo", "kgalefo", "kgathatso", "kgesa", "kgotlello", "kgotso", "kgotsofalo", "kotsi", "lehloeo", "lehlohonolo", "lerato", "leshano", "lonya", "mabe", "makala", "maswabi", "mohau", "molemo", "mona", "monate", "monyaka", "musa", "ntle", "nyahama", "nyatsa", "nyediso", "nyefolo", "qenehelo", "rata", "sebe", "sebete", "sefifi", "thabisa", "thabo", "thetso", "thohako", "tlhekefetso", "tlotla", "tokoloho", "tshabo", "tshediso", "tshehetso", "tshepo", "tshotleho", "tshwarelo", "tshwenyeho"]

```


### Raw model response

```json
[{"word":"tshepahalo","english_gloss":"faithfulness","polarity":"positive","explanation":"Indicates honesty, loyalty, and reliability."},{"word":"botswa","english_gloss":"laziness","polarity":"negative","explanation":"Describes a lack of willingness to work or exert effort, viewed negatively."},{"word":"boikakaso","english_gloss":"arrogance","polarity":"negative","explanation":"Refers to excessive pride or haughtiness."},{"word":"tlhokomelo","english_gloss":"care","polarity":"positive","explanation":"Means taking care of someone or something, showing attentiveness and concern."},{"word":"hlweka","english_gloss":"pure","polarity":"positive","explanation":"Describes cleanliness or purity, often used metaphorically for a pure heart or good intentions."},{"word":"boikokobetso","english_gloss":"humility","polarity":"positive","explanation":"Represents modesty and humbleness, a highly valued trait in Sesotho culture."},{"word":"mamello","english_gloss":"patience","polarity":"positive","explanation":"Refers to endurance and the ability to tolerate hardship without complaining."},{"word":"koduwa","english_gloss":"disaster","polarity":"negative","explanation":"Signifies a tragedy, catastrophe, or severe misfortune."},{"word":"pholoso","english_gloss":"salvation","polarity":"positive","explanation":"Means rescue or deliverance from harm, carrying strong positive and often spiritual connotations."},{"word":"teboho","english_gloss":"gratitude","polarity":"positive","explanation":"Expresses thankfulness and appreciation."},{"word":"kgothatso","english_gloss":"encouragement","polarity":"positive","explanation":"Refers to words or actions that give someone courage, hope, or confidence."},{"word":"bokgabane","english_gloss":"excellence","polarity":"positive","explanation":"Describes virtue, outstanding goodness, or moral excellence."},{"word":"nete","english_gloss":"truth","polarity":"positive","explanation":"Represents honesty, reality, and truthfulness."},{"word":"sello","english_gloss":"wailing","polarity":"negative","explanation":"Refers to crying, weeping, or a plea for help, associated with sadness or distress."},{"word":"bofokoli","english_gloss":"weakness","polarity":"negative","explanation":"Indicates physical or moral frailty and vulnerability."},{"word":"rorisa","english_gloss":"praise","polarity":"positive","explanation":"A verb meaning to commend, glorify, or express high approval."},{"word":"sotla","english_gloss":"mock","polarity":"negative","explanation":"Means to abuse, ill-treat, or deride someone."},{"word":"nyakallo","english_gloss":"joy","polarity":"positive","explanation":"Expresses deep rejoicing, happiness, and celebration."},{"word":"matla","english_gloss":"strength","polarity":"positive","explanation":"Means power or strength, often used to encourage or describe someone capable."},{"word":"bopelotshweu","english_gloss":"kindness","polarity":"positive","explanation":"Literally translates to a white heart, signifying pure intentions, generosity, and kindness."}]
```

## Batch 5

**model:** `gemini-3.1-pro-preview`  
**language:** `sot`  
**time_utc:** `2026-10-09T10:57:35+00:00`  
**batch_id:** `sot-20261009T105735503162Z-5`  
**method:** `zero-shot`  
**prompt_sha256:** `d73a6f49d840d6321ca3328f9543a6b7a3cf321d0253734e53e87f99e45d29de`  

### Prompt

```text
Generate a batch of 20 sentiment-bearing words in Sesotho.

For every candidate, provide:
1. the word in Sesotho;
2. a concise English gloss;
3. a preliminary polarity: positive, negative, or neutral; and
4. a short explanation of its typical emotional meaning.

Requirements:
- Include only words genuinely used in Sesotho.
- Do not invent, transliterate, or silently borrow words from another language.
- Exclude proper names, punctuation, and complete sentences.
- Exclude every item in the exclusion list below.
- The candidate should be a single lexical item (not a phrase).
- Produce at most 20 candidates. Do not sacrifice quality to meet the number.
- Use 'neutral' only when it is a defensible polarity category.
- Return only a valid JSON array of objects with keys: word, english_gloss, polarity, explanation.

Exclusion list: ["babatsa", "bobe", "bofokoli", "bofuma", "bohale", "bohlale", "bohloko", "boikakaso", "boikokobetso", "bokgabane", "bokhopo", "bopelonomi", "bopelotshweu", "botswa", "hlompho", "hlonama", "hloya", "hlweka", "kamohelo", "kananelo", "katleho", "kgalalelo", "kgalefo", "kgathatso", "kgesa", "kgothatso", "kgotlello", "kgotso", "kgotsofalo", "koduwa", "kotsi", "lehloeo", "lehlohonolo", "lerato", "leshano", "lonya", "mabe", "makala", "mamello", "maswabi", "matla", "mohau", "molemo", "mona", "monate", "monyaka", "musa", "nete", "ntle", "nyahama", "nyakallo", "nyatsa", "nyediso", "nyefolo", "pholoso", "qenehelo", "rata", "rorisa", "sebe", "sebete", "sefifi", "sello", "sotla", "teboho", "thabisa", "thabo", "thetso", "thohako", "tlhekefetso", "tlhokomelo", "tlotla", "tokoloho", "tshabo", "tshediso", "tshehetso", "tshepahalo", "tshepo", "tshotleho", "tshwarelo", "tshwenyeho"]

```


### Raw model response

```json
[{"word":"hlora","english_gloss":"suffer","polarity":"negative","explanation":"Indicates experiencing emotional or physical pain and hardship."},{"word":"hlokofatsa","english_gloss":"hurt","polarity":"negative","explanation":"Means to inflict pain or torture, carrying a strong negative sentiment."},{"word":"pelaelo","english_gloss":"doubt","polarity":"negative","explanation":"Expresses suspicion, uncertainty, or lack of trust."},{"word":"hlohonolofatsa","english_gloss":"bless","polarity":"positive","explanation":"Means to bestow blessings or favor, bringing joy and positive regard."},{"word":"tlontlolla","english_gloss":"humiliate","polarity":"negative","explanation":"Refers to disgracing or degrading someone, causing deep shame."},{"word":"dihlong","english_gloss":"shame","polarity":"negative","explanation":"Represents embarrassment, shyness, or disgrace."},{"word":"qabana","english_gloss":"quarrel","polarity":"negative","explanation":"Denotes arguing or falling out with someone, indicating relational conflict."},{"word":"moferefere","english_gloss":"chaos","polarity":"negative","explanation":"Refers to trouble, disorder, or a riot, evoking feelings of instability."},{"word":"tlokotsi","english_gloss":"disaster","polarity":"negative","explanation":"Describes a tragedy or severe misfortune, carrying heavy sorrow or fear."},{"word":"natefelwa","english_gloss":"enjoy","polarity":"positive","explanation":"Means to find pleasure or delight in an experience."},{"word":"thakgala","english_gloss":"rejoice","polarity":"positive","explanation":"Expresses extreme happiness, cheerfulness, and jubilation."},{"word":"kgathala","english_gloss":"tire","polarity":"negative","explanation":"Means to become exhausted or weary, often associated with fatigue or giving up."},{"word":"tshwenya","english_gloss":"bother","polarity":"negative","explanation":"Means to annoy, disturb, or cause worry to someone."},{"word":"phomolo","english_gloss":"rest","polarity":"positive","explanation":"Implies relief, peace, and recovery from exhaustion."},{"word":"tumelo","english_gloss":"faith","polarity":"positive","explanation":"Represents belief, trust, and spiritual confidence."},{"word":"ferekanya","english_gloss":"confuse","polarity":"negative","explanation":"Means to frustrate, perplex, or disrupt someone's peace of mind."},{"word":"kgoboho","english_gloss":"disgrace","polarity":"negative","explanation":"Refers to a state of shame, scandal, or loss of reputation."},{"word":"sireletsa","english_gloss":"protect","polarity":"positive","explanation":"Means to guard or defend, providing a sense of safety and care."},{"word":"hanyetsa","english_gloss":"oppose","polarity":"negative","explanation":"Denotes resistance, contradiction, or defiance against something or someone."},{"word":"dumellana","english_gloss":"agree","polarity":"positive","explanation":"Indicates harmony, consensus, and mutual understanding."}]
```
