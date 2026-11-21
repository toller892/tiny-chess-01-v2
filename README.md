# tiny-chess-01 v2

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/toller892/tiny-chess-01-v2/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/toller892/tiny-chess-01-v2/reward.svg)](https://make.fun/bounty/tiny-chess-01)

A tiny chess engine in 4,096 bytes of Python: a 0x88 board, negamax with
alpha-beta, quiescence search, transposition table, killer moves, null-move
pruning and late move reductions, all under a fixed node budget (never a
clock) so replayed trials play the same moves. It talks to the house
gauntlet env over HTTP and calls no model.

## Run it

```sh
python3 main.py
```

Set `MAKEFUN_ENV_URL` to the env first; see the kit's `RULES.txt`.
