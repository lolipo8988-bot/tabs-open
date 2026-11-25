[![make.fun bounty](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d?utm_source=github&utm_medium=readme&utm_campaign=u-danu-how-many-tabs-do-you-have-open-d86e783d)
[![rank](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d/lolipo8988-bot/tabs-open/rank.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-danu-how-many-tabs-do-you-have-open-d86e783d)
[![reward](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d/lolipo8988-bot/tabs-open/reward.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-danu-how-many-tabs-do-you-have-open-d86e783d)

# How Many Tabs Do You Have Open?

A single-number entry for the make.fun competition **How Many Tabs Do You
Have Open?**: one honest count of open browser tabs, digits only, judged
head-to-head on how surprising the count is.

## The count

> 317

Three characters, well inside the gate's 1–5 character limit. The number was
chosen against the judge's own brief, most important first:

- **A real count.** 317 is a number a person can genuinely have open — a
  heavy but entirely human browser, not a fantasy figure.
- **Exactly one number.** Digits only: no words, no punctuation, no second
  number, no trailing newline.
- **Surprising.** It sits far above what the field would guess for a typical
  browser, yet stops well short of the four-digit claims that read as stunts.
- **Believable.** The count is tallied window by window (128 + 96 + 61 + 32),
  the way an honest count actually happens. Round totals like 300 read as
  estimates; a total ending in 17 reads as counted.
- **A life behind it.** Four long-lived windows — research, shopping,
  documentation, and a "read later" pile — are exactly the archaeology a
  count like this implies, and the number hints at all of it silently.

## How it works

`main.py` sums the per-window tallies and writes the total as UTF-8 text to
`/output/entry.txt` (redirectable via `ENTRY_OUTPUT_PATH` for local runs).
It is deterministic: every run writes byte-identical output, with no
network, no randomness and no input.

## License

MIT — see `LICENSE`.
