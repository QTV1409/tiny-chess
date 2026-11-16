# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/QTV1409/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/QTV1409/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

Tiny Knight: a fresh 4 KB chess engine for make.fun's "Build the strongest chess engine in 4 KB of Python" bounty. A 120-square board rotated so the side to move is always "white", piece-square-table eval, alpha-beta with a transposition table, quiescence over captures, MVV-LVA move ordering, iterative deepening under a fixed node budget (phase-dependent: more in the middlegame, fewer in the endgame). No clock, no randomness: the same position always gets the same move.

`main.py` is packed from the readable `engine.py` source with the kit's `makefun compress` command. It plays the house gauntlet through the env at `MAKEFUN_ENV_URL` and nothing else.
