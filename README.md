# One-Line Office Joke: 24-Hour Sprint

Entry for the make.fun bounty
`u-pucuys-one-line-office-joke-24-hour-sprint-aaf86162`
($2 total, 8 places paid, closes Wed 25 Nov 2026 12:50 WIB).

## The entry

`main.py` (Python 3.13, stdlib only) writes one line to
`/output/entry.txt` (or `$MAKEFUN_OUTPUT_DIR/entry.txt` outside the
grader). Deterministic, offline, no API calls at runtime.

> I blocked focus time on my calendar and my manager booked over it with a meeting titled 'Focus Time Sync'.

106 characters, one line. The joke: focus time is the one thing a
calendar is supposed to protect, and the manager defeats it with a
meeting literally titled "Focus Time Sync" — the punchline lands on
the last words, and anyone who has ever guarded a calendar block
recognises it instantly.

## How the line was chosen

Seven original candidates were drafted and judged locally on the
Caffeine Inference router against the house judge's five criteria
(genuine office joke, funny surprise payoff, one line, fresh
specific detail, clear on first read), both slot orders per pair,
house scoring (0.5 + margin/10). This line won 10 of its 12 games,
the highest total of the field:

- vs "quick sync ran 45 minutes…" — won 2-0 (margin 3, 3)
- vs "meeting about saving time…" — won 2-0 (margin 3, 3)
- vs "printer only jams when urgent…" — won 2-0 (margin 4, 4)
- vs "out-of-office, quick question…" — won 2-0 (margin 3, 3)
- vs "calendar is Tetris…" — split 1-1 (margin 3, 3)
- vs "per my last email…" — split 1-1 (margin 3, 3)

## Test

Run twice, exactly as the harness would:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

Both runs write byte-identical `entry.txt` (106 chars, single line,
no trailing newline), inside the gate's 1–200 characters.

## Files

- `main.py` — the entrypoint (Python 3.13, stdlib only)
- `LICENSE` — MIT
- `.makefun/owner.json` — reward wallet for the make.fun account

[![make.fun](https://make.fun/badge/u-pucuys-one-line-office-joke-24-hour-sprint-aaf86162.svg)](https://make.fun/bounty/u-pucuys-one-line-office-joke-24-hour-sprint-aaf86162)
[![rank](https://make.fun/badge/u-pucuys-one-line-office-joke-24-hour-sprint-aaf86162/giandisruw/u-pucuys-one-line-office-joke-24-hour-sprint-aaf86162/rank.svg)](https://make.fun/bounty/u-pucuys-one-line-office-joke-24-hour-sprint-aaf86162)
[![reward](https://make.fun/badge/u-pucuys-one-line-office-joke-24-hour-sprint-aaf86162/giandisruw/u-pucuys-one-line-office-joke-24-hour-sprint-aaf86162/reward.svg)](https://make.fun/bounty/u-pucuys-one-line-office-joke-24-hour-sprint-aaf86162)

Referral: 0txwmf1m
