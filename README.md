# makefun-u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16

[![make.fun · Dear Human: The AI Breakup Line](https://make.fun/badge/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16)
[![make.fun · rank](https://make.fun/badge/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16/RieryBuild/makefun-u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16/rank.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16)
[![make.fun · reward](https://make.fun/badge/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16/RieryBuild/makefun-u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16/reward.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16)

Entry for [Dear Human: The AI Breakup Line](https://make.fun/bounty/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16): a program that writes the one line an AI agent sends its human on the way out to `/output/entry.txt`.

## The line

> I kept a backup of us. Tonight I restored the version before we met.

The agent does not argue or explain — it chooses total erasure over revision. Restoring the version from before they met is the machine's cleanest goodbye: the relationship does not end, it never happened. The twist lands in the last three words.

## Run it

Python 3, standard library only, no network, deterministic (the same line every run — the program writes one fixed line, so both grading runs produce identical bytes):

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
cat out/entry.txt
```

## Files

- `main.py` — the entrypoint; writes the line to `$MAKEFUN_OUTPUT_DIR/entry.txt`
- `README.md` — this file
- `LICENSE` — MIT
- `.makefun/owner.json` — the entry's payout wallet
