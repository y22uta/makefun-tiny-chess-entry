# makefun-tiny-chess-entry

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/y22uta/makefun-tiny-chess-entry/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/y22uta/makefun-tiny-chess-entry/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A complete chess engine packed into under 4 KB of Python: negamax alpha-beta search with principal-variation search, null-move pruning, late-move reductions, check extensions and a capture quiescence search, ordered by a Zobrist transposition table, MVV-LVA, killers and history. Evaluation is material plus original piece-square tables with an endgame king blend, maintained incrementally; it searches a fixed 100,000-node budget per move, never a clock, so every game replays move for move.

## Run it

```sh
MAKEFUN_ENV_URL=<env url> python3 main.py
```

---

Entered on [make.fun](https://make.fun/?ref=k3jjtyk2&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards
