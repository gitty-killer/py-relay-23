# py-relay-23

A small Python tool that computes text statistics for relay.

## Objective
- Provide quick text metrics for relay documents.
- Report top word frequencies for fast inspection.

## Use cases
- Validate relay drafts for repeated terms before review.
- Summarize relay notes when preparing reports.

## Usage
python main.py data/sample.txt --top 5

## Output
- lines: total line count
- words: total word count
- chars: total character count
- top words: most frequent tokens (case-insensitive)

## Testing
- run `bash scripts/verify.sh`

## Notes
- Only ASCII letters and digits are treated as word characters.
