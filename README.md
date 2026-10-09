# PAAISSA Supplementary Evidence — Sesotho and Setswana

This package organises the exact uploaded files for six model/language combinations. Original files are preserved unchanged. Markdown reports are readable conversions from JSONL records, not screenshots or independently verified results.

| Provider | Language | Original evidence | Notes |
|---|---|---|---|
| OpenAI GPT-4.1 | Setswana | Markdown raw response | Prompt ID CG-01; one example batch |
| OpenAI GPT-4.1 | Sesotho | Markdown raw response | Prompt ID CG-01; one example batch |
| Gemini 3.1 Pro Preview | Setswana | JSONL API logs | Five records, raw responses included |
| Gemini 3.1 Pro Preview | Sesotho | JSONL API logs | Five records, raw responses included |
| Claude Opus 4.5 | Setswana | JSONL API logs | Six records, raw responses included |
| Claude Opus 4.5 | Sesotho | Candidates CSV only | Original raw requests/responses **not included** |

## Methodological cautions

- All entries must be treated as model-generated candidates pending human validation; these files do not establish linguistic correctness.
- Do not present the Claude Sesotho CSV as a raw API response or claim the exact prompts are recorded in it.
- Gemini response fields may use `polarity` rather than `preliminary_polarity`; normalise in downstream processing and document the mapping.
- This collection is additional evidence; it does not constitute evidence of complete full-scale experiments or of the final lexicon sizes/metrics cited in the manuscript.
- The OpenAI files are examples from one batch per language, not full execution histories.
- Do not include API tokens or personal credentials in public GitHub uploads.
- Llama is intentionally absent because it was not used in the reported experiment.

## Suggested citation text for the manuscript

Representative Sepedi outputs are shown in Figure 2. Additional model-language evidence for Sesotho and Setswana, including archived prompts and model responses where recorded, is provided in the accompanying repository. The Claude Sesotho materials presently contain candidate-level exports only.


## Update: Claude Sesotho successful API evidence (9 October 2026)

The file `claude/sesotho/claude_sot_evidence_successful.jsonl` contains 5 successful Claude Opus 4.5 batches and 100 raw generated entries, including prompts, responses, timestamps and API request metadata. A Markdown rendering is included. The earlier failed API attempts are retained separately for transparency. These raw candidate entries require independent linguistic validation and must not be presented as verified lexicon entries.
