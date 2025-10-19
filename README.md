## Prompt Tester (prompt_tester.py)
Scans prompts for possible prompt-injection keywords and logs results.

### Usage
Run with built-in prompts:
  python3 prompt_tester.py

Run with your own file (one prompt per line):
  python3 prompt_tester.py myprompts.txt

Edit detection rules:
  patterns.txt  # one keyword per line

Outputs:
  scan_YYYYMMDD_HHMMSS.txt  # new log file per run with a pattern breakdown

