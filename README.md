# LLM-Assisted Sentiment Lexicons for Sepedi, Sesotho, and Setswana

This repository contains the reproducibility materials accompanying the paper on an LLM-assisted, human-centred framework for constructing sentiment lexicons for Sepedi, Sesotho, and Setswana.

The framework comprises five stages:

1. Data preparation
2. Multi-model LLM candidate generation
3. Automated candidate refinement
4. Native-speaker validation and human-feedback refinement
5. Held-out evaluation

The final lexicons reported in the paper contain 2,847 Sepedi entries, 2,634 Sesotho entries, and 2,912 Setswana entries.

## Repository contents

| Path | Description |
|---|---|
| `prompts.md` | Complete prompt templates for candidate generation, scoring, contextual analysis, and refinement |
| `model_configuration.md` | Reporting table for exact models, access dates, decoding settings, and repetitions |
| `annotation_guidelines.md` | Instructions used by the three annotators |
| `data/README.md` | Data statement and required benchmark documentation |
| `schemas/lexicon_entry.schema.json` | JSON Schema for a final lexicon entry |
| `schemas/human_annotation.schema.json` | JSON Schema for one annotator judgement |
| `examples/lexicon_sample.json` | Illustrative records showing the expected output structure |
| `CITATION.cff` | Citation metadata |
| `LICENSE` | MIT licence for repository code and templates |

## Evaluation separation

The held-out evaluation resource contains 1,000 manually annotated samples per language. Three annotators assessed the samples. Held-out records must not be included in prompt development, candidate generation, contextual-example generation, candidate refinement, or human-feedback prompts used to construct the lexicons.

The repository does not redistribute source corpora or held-out annotations unless their licences and ethics conditions explicitly permit redistribution. See `data/README.md`.

## Reproducibility requirements

Before releasing the repository with the paper, complete `model_configuration.md` using the original API logs. Report the exact model identifiers rather than product-family names. Also record access dates, temperature, maximum output tokens, sampling parameters, number of runs, batching rules, and output-filtering rules.

If the prompt templates in `prompts.md` were reconstructed after the experiment, describe them as representative templates. Do not claim that they are verbatim prompts unless they match the prompts recorded during the experiments.

## Suggested paper statement

> The prompt templates, output schemas, annotation instructions, and reproducibility materials are available in the accompanying repository: https://github.com/YOUR-USERNAME/sotho-tswana-sentiment-lexicons.

Replace `YOUR-USERNAME` after creating the GitHub repository.

## Licence

The code, schemas, and prompt templates in this repository are released under the MIT License. Third-party corpora, annotations, and model outputs remain subject to their original licences and terms of use.

