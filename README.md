# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/youngzim/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/youngzim/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A complete chess engine in 4,074 bytes of Python: negamax search with alpha-beta pruning, quiescence, a transposition table with Zobrist hashing, and full rules (castling, en passant, promotion, draws) — lzma-packed behind a small latin-1 stub. It plays deterministic chess on a fixed node budget and never reads the clock. In the kit's local gauntlet it averaged Elo ~1550 across two practice instances against the sunfish-4k baseline's ~1365, clearing the 1154 practice floor in both.

## Run it

```sh
python3 main.py
```

The engine speaks UCI on stdin/stdout (`uci`, `position`, `go`, `quit`).

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
