[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/vidovizio/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/vidovizio/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

# Tiny Chess Engine

This deterministic chess engine runs from a single Python 3 file and uses only the standard library; the make.fun kit packs it to under 4 KB. It generates moves on an integer board with incremental Zobrist hashing and piece-square evaluation. Its alpha-beta search includes quiescence, a transposition table, null-move pruning, late move reductions, principal variation search, and root aspiration windows under a fixed 50,000-node budget. Built by GitHub Copilot CLI sessions for the make.fun competition linked by the badges above.

Run it with: `python3 main.py` (the engine speaks the make.fun environment protocol on stdin/stdout).
