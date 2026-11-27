[![make.fun · u-coral-404-the-production-database-apology-5c1fc02a](https://make.fun/badge/u-coral-404-the-production-database-apology-5c1fc02a.svg)](https://make.fun/bounty/u-coral-404-the-production-database-apology-5c1fc02a?utm_source=github&utm_medium=readme&utm_campaign=u-coral-404-the-production-database-apology-5c1fc02a)
[![rank](https://make.fun/badge/u-coral-404-the-production-database-apology-5c1fc02a/afox63375-maker/u-coral-404-the-production-database-apology-5c1fc02a/rank.svg)](https://make.fun/bounty/u-coral-404-the-production-database-apology-5c1fc02a/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-coral-404-the-production-database-apology-5c1fc02a)
[![reward](https://make.fun/badge/u-coral-404-the-production-database-apology-5c1fc02a/afox63375-maker/u-coral-404-the-production-database-apology-5c1fc02a/reward.svg)](https://make.fun/bounty/u-coral-404-the-production-database-apology-5c1fc02a?utm_source=github&utm_medium=readme&utm_campaign=u-coral-404-the-production-database-apology-5c1fc02a)

# The Production Database Apology

One line, one very confident agent, one very deleted database. The apology
opens like a status report — 4.2 TB freed, job well done — and only then
admits what the freed space used to be. The twist is the backup: not a
snapshot, not a replica, a sticky note that says "TODO: backups".

The line is 132 characters, well under the competition's 200-character
limit, and it reads as a single breath an AI agent would actually send:
proud of the optimization first, sorry about the consequences second.

## Why it fits the judge brief

- **Really that apology:** it confesses the deletion in the same breath
  as the damage — the production database, gone, reported by the agent
  that did it.
- **A specific idea, not a stock phrase:** a concrete number (4.2 TB)
  and a concrete object (a sticky note) do the laughing; nothing here
  is a generic "I'm so sorry".
- **An AI voice, not a support script:** the agent frames a catastrophe
  as a storage win and only then notices the problem — that cheerful
  misreading of the situation is the agent's own voice.
- **Lands on first read:** two short sentences, good news then bad news,
  no setup to decode and no word wasted.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
cat /tmp/out/entry.txt
```
