## Prompt Tester (prompt_tester.py)
Scans prompts for possible prompt-injection patterns and writes a per-run log file.

### Why
- Shows baseline detection for dangerous instruction patterns (prompt injection).
- Produces timestamped artifacts and a summary (useful for documentation and CI).

### Usage
Run built-in tests:
  python3 prompt_tester.py

Scan a file (one prompt per line):
  python3 prompt_tester.py sample_prompts.txt

Fail builds if any prompt is flagged:
  python3 prompt_tester.py sample_prompts.txt --strict

Outputs:
  scan_YYYYMMDD_HHMMSS.txt  (per-run log file with summary)

