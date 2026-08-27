# Model and Generation Configuration

Complete this table using the original experiment logs before making the repository public. Product-family names such as “GPT”, “Claude”, or “Gemini” are insufficient for reproducibility.

| Provider | Exact model identifier | Access date | Temperature | Maximum output tokens | Top-p | Seed | Runs | Role in framework |
|---|---|---|---:|---:|---:|---:|---:|---|
| Provider 1 | To be copied from API logs | YYYY-MM-DD | 0 | To verify | To verify | To verify | To verify | Candidate generation/scoring |
| Provider 2 | To be copied from API logs | YYYY-MM-DD | 0 | To verify | To verify | To verify | To verify | Candidate generation/scoring |
| Provider 3 | To be copied from API logs | YYYY-MM-DD | 0 | To verify | To verify | To verify | To verify | Candidate generation/scoring |
| Provider 4 | To be copied from API logs | YYYY-MM-DD | 0 | To verify | To verify | To verify | To verify | Candidate generation/scoring |

## Additional settings to report

- API or library version
- System and user prompts used at every stage
- Number of candidates requested per batch
- Number of contextual sentences generated per candidate
- Candidate exclusion-list construction
- Retry and failure-handling rules
- JSON parsing and repair rules
- Duplicate detection and normalisation
- Majority-vote rule and tie handling
- Intensity aggregation rule
- Cross-model disagreement rule
- Threshold for referral to human review
- Manual filtering and adjudication procedures

Do not replace unverified settings with values taken from model documentation. Report the values actually supplied to the API during the experiment.

