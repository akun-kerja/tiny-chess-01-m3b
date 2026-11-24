# tiny-chess-01-m3b

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/akun-kerja/tiny-chess-01-m3b/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/akun-kerja/tiny-chess-01-m3b/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

M3b chess engine in 4,026 bytes of Python, built for [make.fun's tiny-chess-01 bounty](https://make.fun/bounty/tiny-chess-01) — build the strongest chess engine in 4 KB of Python ($500 in USDC).

Alpha-beta search with PVS, transposition table, null-move pruning, LMR, quiescence with check evasion, and a tapered PeSTO evaluation with a pawn shield. Fixed budget of 30,000 nodes per move, fully deterministic (no wall clock). Practice Elo 1,407 (trial-0 1,364, trial-1 1,451, 8-game 1,326).

Run: `python3 main.py` (the harness sets `MAKEFUN_ENV_URL`).

Referral code: `kajzbdrj`
