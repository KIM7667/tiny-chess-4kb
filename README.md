# tiny-chess-4kb

A 4 KB chess engine for make.fun's tiny-chess-01 bounty: alpha-beta search
with quiescence, transposition table, killer moves and null-move pruning,
pure Python 3.13 standard library. `main.py` is the packed entrypoint
(`makefun compress` of `engine.py`); `engine.py` is the readable source.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```
