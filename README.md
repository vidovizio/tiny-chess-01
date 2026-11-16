# Tiny Chess

Deterministic Python chess engine for the make.fun tiny-chess-01 gauntlet.
It generates and validates legal moves, then searches with iterative-deepening
negamax alpha-beta, quiescence, move ordering, and a Zobrist transposition
table. Search is bounded by a fixed budget of 50,000 nodes per move.
