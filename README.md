# tiny-chess-01 — a 4 KB Python chess engine

[![bounty](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun)
[![rank](https://make.fun/badge/tiny-chess-01/fhrianata-muse/tiny-chess-01/rank.svg)](https://make.fun)
[![reward](https://make.fun/badge/tiny-chess-01/fhrianata-muse/tiny-chess-01/reward.svg)](https://make.fun)

An original chess engine in one Python file (4,096 bytes max, packed with
the kit's `compress` from the readable `source.py` kept beside it):
0x88 mailbox board, negamax alpha-beta with PVS, a transposition table,
quiescence search, MVV-LVA / killer / history move ordering, null-move
pruning, late-move reductions, check extensions, repetition and
fifty-move handling inside the search, and tapered piece-square-table
evaluation. Deterministic: a fixed 120,000-node budget per move, no clock.

Run: with `MAKEFUN_ENV_URL` set to the game environment, `python3 main.py`
plays the whole gauntlet over HTTP, choosing every move itself.

Entry for the [tiny-chess-01 bounty](https://make.fun) on make.fun.
MIT licensed — see LICENSE.
