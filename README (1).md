# Data Statement

## Sources

The study reports textual resources drawn from multilingual editions of *Vuk'uzenzele*, the NCHLT corpora, and additional African-language resources. The exact additional datasets, versions, languages, domains, licences, and retained quantities must be listed in the paper and repository before release.

## Preprocessing

PDF documents were extracted using PyPDF2 and pdfplumber. Regular expressions supported pattern-based cleaning, and pandas supported record structuring. The reported pipeline included Unicode normalisation, duplicate removal, sentence segmentation, language identification, and exclusion of malformed or predominantly non-target-language content.

Approximately 40% of the collected material was reportedly excluded. The stated composition of the discarded subset was 27% heavily code-switched content, 31% corrupted text, and 42% non-standard orthography. Release the underlying counts or preprocessing logs if available; do not attribute these project-specific percentages to external publications.

## Held-out evaluation

- Languages: Sepedi, Sesotho, and Setswana
- Evaluation size: 1,000 samples per language
- Annotators: three
- Required labels: positive, negative, or neutral
- Required documentation: sampling procedure, class distribution, domain distribution, annotator qualifications, agreement statistic, adjudication procedure, and leakage controls

## Redistribution

This repository does not include copyrighted articles, restricted corpora, private annotation data, or third-party datasets by default. Add only files whose licences, consent conditions, and institutional requirements permit public redistribution.

If the held-out data cannot be released, provide aggregate statistics, stable record hashes where appropriate, and scripts that reproduce the evaluation for authorised users without exposing restricted text.

