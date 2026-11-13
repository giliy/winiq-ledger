# WinIQ — the public ledger / היומן הציבורי

The record of [WinIQ](https://winiq.co.il/), a Hebrew analysis site for Winner 16 (Israel's weekly 16-game football pool).
A bot copies these files here after every scheduled run. They only ever grow: a row is never edited or deleted, and
this repository's history shows every version. Each file is also served at `https://winiq.co.il/ledger/<file>` with its
SHA-256 on https://winiq.co.il/record/#verify, and snapshotted at the Internet Archive.

| File | What it holds |
|---|---|
| `probs.csv` | The chance of 1 / X / 2 for each game, logged before the round's deadline whenever it moves more than 2 points |
| `tickets.csv` | WinIQ's recommended tickets (8 / 36 / 144 columns). The official one = the last row before the deadline |
| `results.csv` | Each official ticket graded after the round: the best column's hits out of 16 |
| `baseline.csv` | The scoreboard's reference: a favourites-only ticket at the same budget (same builder, no lean away from the crowd) |
| `scoreboard.csv` | Ours vs the favourites ticket, per round and budget: hits and winning columns per prize tier |

The scoreboard comparison was frozen on 2026-11-13, before the first graded round, and does not change.
Results are graded only from the official results. Times are UTC.

---

כל הטפסים והסיכויים של WinIQ נרשמים כאן לפני סגירת המחזור ונבדקים אחריו — גם כשמפסידים. הקבצים רק גדלים; ההיסטוריה של
המאגר מראה כל גרסה. WinIQ הוא אתר ניתוח עצמאי ואינו קשור למועצה להסדר ההימורים בספורט או ל-Winner. אין באמור המלצה להמר. 18+.
