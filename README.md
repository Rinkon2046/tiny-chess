# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Rinkon2046/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Rinkon2046/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python, built for make.fun's tiny-chess-01
bounty: negamax alpha-beta search with iterative deepening under a fixed
node budget (deterministic, never a clock), quiescence over captures,
promotions and check evasions, a transposition table that persists
across moves, MVV-LVA + killer move ordering, in-search repetition
scoring against the game history, and a material + piece-square
evaluation.

The engine is `main.py` alone (Python 3.13, standard library only). It
plays through the env at `MAKEFUN_ENV_URL`: `python3 main.py`.
