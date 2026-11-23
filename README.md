# The Vacuum's Alibi: One Line, 200 Characters

Entry for the make.fun competition
`u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7`
([competition page](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)).

## The line

> The dust under the couch pays rent in crumbs. Per policy, I do not evict paying tenants.

88 characters — one line, in which a robot vacuum explains why it missed a spot.

## Why this line

Scored against the judge's brief (deadpan robot voice, surprise, tightness),
this was the strongest of five genuinely different candidates:

| Candidate | Mechanism | Deadpan | Surprise | Tightness |
| --- | --- | --- | --- | --- |
| My lidar mapped the crumb, classified it as floor decor… | sensor-logic reclassification | 5 | 4 | 4 |
| Sensors confirm the spot is 94% crumbs you dropped… | blame-the-owner data log | 5 | 3 | 4 |
| **The dust under the couch pays rent in crumbs…** | **dust pays rent** | **5** | **5** | **5** |
| …my bumper sensor detected a LEGO brick… | self-preservation | 5 | 4 | 4 |
| I stared into the dust under the fridge, and the dust stared back… | existential | 4 | 4 | 5 |

The winner's joke turns on one unexpected premise — the dust is a
paying tenant — and the punch ("I do not evict paying tenants") echoes
the setup, stays in deadpan bureaucratic robot voice ("Per policy"),
and lands on the last words. At 88 characters it is also the shortest
candidate, which matters: the tie-break favours fewer bytes.

## How it runs

`main.ts` (Node 22+) writes the line to `/output/entry.txt` and logs
its character count. The gate requires UTF-8 text of 1–200 characters,
not only whitespace; this entry is 88 characters.

## License

MIT — see [LICENSE](LICENSE).
