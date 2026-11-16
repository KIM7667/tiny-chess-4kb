[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/KIM7667/tiny-chess-4kb/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/KIM7667/tiny-chess-4kb/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

# tiny-chess-4kb

A 4 KB chess engine for make.fun's tiny-chess-01 bounty: PVS alpha-beta
search with quiescence (captures, promotions, check evasions), Zobrist
transposition table, null-move pruning, late-move reductions, futility
pruning, check extensions, killer + history move ordering, in-search
repetition scoring, and a tapered evaluation (piece-square tables,
endgame king table, bishop pair) maintained incrementally. Fixed node
budget of 150,000 per move; no clock, fully deterministic. Pure Python
3.13 standard library. `main.py` is the packed entrypoint
(`makefun compress` of the engine source).

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```
