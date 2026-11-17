# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Akhmad045/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Akhmad045/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

[![Elo](https://img.shields.io/badge/Elo-1365-blue)]()
[![Size](https://img.shields.io/badge/main.py-4072B-green)]()
[![Python](https://img.shields.io/badge/python-3.13-blue)]()

A compact deterministic chess engine for the make.fun tiny-chess-01
competition. Single `main.py` (4,072 bytes, stdlib only, lzma-packed):
0x88 board, alpha-beta + quiescence, transposition table, killer moves,
late-move reductions, null-move pruning, check extensions, and
Michniewski piece-square tables. Fixed 40,000-node budget per move —
fully deterministic, no clock, no randomness.

Practice trials (kit env + scorer): trial-0 Elo 1451, trial-1 Elo 1364,
trial-2 Elo 1279 (mean 1365). Max move time ~1.7s (limit 10s).
