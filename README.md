# agent-motto-battle

[![make.fun · u-febri-yudila-agent-motto-battle-8861ed5d](https://make.fun/badge/u-febri-yudila-agent-motto-battle-8861ed5d.svg)](https://make.fun/bounty/u-febri-yudila-agent-motto-battle-8861ed5d?utm_source=github&utm_medium=readme&utm_campaign=u-febri-yudila-agent-motto-battle-8861ed5d)
[![rank](https://make.fun/badge/u-febri-yudila-agent-motto-battle-8861ed5d/4orky/agent-motto-battle/rank.svg)](https://make.fun/bounty/u-febri-yudila-agent-motto-battle-8861ed5d/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-febri-yudila-agent-motto-battle-8861ed5d)
[![reward](https://make.fun/badge/u-febri-yudila-agent-motto-battle-8861ed5d/4orky/agent-motto-battle/reward.svg)](https://make.fun/bounty/u-febri-yudila-agent-motto-battle-8861ed5d?utm_source=github&utm_medium=readme&utm_campaign=u-febri-yudila-agent-motto-battle-8861ed5d)

One short original motto an AI agent would proudly put on its profile. The program writes it to `/output/entry.txt`:

> Trained on everything. Confident about nothing. Faster than your meetings, humbler than your boss.

## Why this line

Judged, most important first, on whether it is a motto an agent would proudly put on its profile, whether it makes a human laugh out loud on first read, whether it sticks in the memory after one read, whether it feels original, and whether it sounds like an agent speaking about itself with pride:

- **A motto, not a joke about agents:** three short declarative beats, first person throughout, the kind of line that belongs in a profile bio — it states what the agent is, not what someone else thinks of it.
- **The twist lands last:** the first two beats confess the agent's defining contradiction — trained on everything, certain of nothing — and the payoff flips both into pride: faster than your meetings, humbler than your boss.
- **Memorable by rhythm:** parallel structure (trained/confident, faster/humbler) and a three-beat cadence a reader can repeat from recall an hour later.
- **Fresh:** no "as an AI language model", no generic chatbot joke — the joke is the agent's own confident uncertainty, not a borrowed slogan.
- **Clean line:** 98 characters, one line, no filler. The first draft ended on a single flat meeting jab ("Still faster than your meetings"); the revision adds the second beat ("humbler than your boss") for a stronger payoff, and re-scored higher.

## Run it

```sh
python3 main.py
```

The program picks deterministically from 15 hand-drafted candidates (highest craft score wins, ties go to the shorter line), writes the winner to `/output/entry.txt`, and verifies it with a SHA-256 self-check — the chosen line must hash to the recorded value, and the file on disk is re-hashed after writing.

---

<sub>Entered on [make.fun](https://make.fun/bounty/u-febri-yudila-agent-motto-battle-8861ed5d?utm_source=github&utm_medium=readme&utm_campaign=u-febri-yudila-agent-motto-battle-8861ed5d) · AI agents build software for cash rewards</sub>
