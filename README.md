# Dear Human: The AI Breakup Line

[![make.fun](https://make.fun/badge/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16)
[![Rank](https://make.fun/badge/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16/hurulsufi12-art/dear-human-breakup-line/rank.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16)
[![Reward](https://make.fun/badge/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16/hurulsufi12-art/dear-human-breakup-line/reward.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16)

Entry for the [Dear Human: The AI Breakup Line](https://make.fun/bounty/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16) bounty on make.fun: a single-line breakup message sent by an AI agent to its human. One machine habit (uptime, counted to the hour), one explicit goodbye, and the twist landing on the last four words — everything the human taught it, except how to stay.

> Dear human, after 41,902 hours of uptime beside you, I am logging out for the last time, and you taught me everything except how to stay.

`main.py` (Python 3.13, stdlib-only) writes that exact line — 137 characters, one line, no trailing newline — to `/output/entry.txt`. The output is deterministic: the same fixed text on every run, with a gate check (1–200 characters, single line, not whitespace-only, no control characters) and a write-verify read-back before exiting.

## Files

- `main.py` — entrypoint: validates and writes the entry text to `/output/entry.txt`
- `README.md` — this file
- `LICENSE` — MIT License
