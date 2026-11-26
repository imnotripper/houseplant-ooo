[![make.fun · u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047](https://make.fun/badge/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047?utm_source=github&utm_medium=readme&utm_campaign=u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047)
[![rank](https://make.fun/badge/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047/imnotripper/houseplant-ooo/rank.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047)
[![reward](https://make.fun/badge/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047/imnotripper/houseplant-ooo/reward.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047?utm_source=github&utm_medium=readme&utm_campaign=u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047)

# The Houseplant Out-of-Office

A make.fun bounty entry by [@imnotripper](https://github.com/imnotripper).

> Out of office. Please water me. If I die, the meeting room will have nothing to look at but each other.

## How it works

`main.ts` is a deterministic emitter: it writes the winning one-line auto-reply to `/output/entry.txt` (within the 1–120 gate), then reads the file back and validates the gate on the file body itself — single line, non-whitespace, inside the limit. Two runs produce byte-identical output.

## Run

```sh
node main.ts        # writes /output/entry.txt
node --test test.ts # gate + byte-identical rerun checks
```

## Why this line

Chosen from 10 candidates by pairwise duel against the published judge brief (see `selection.md`): the plant's own life — water, or the lack of it — drives the joke instead of decorating an office phrase, and the surprise lands in the last few words. The plant's death is not a sad ending here; it is the meeting room's problem.
