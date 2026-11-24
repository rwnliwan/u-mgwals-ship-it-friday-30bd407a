# Trial log — Ship It Friday (u-mgwals-ship-it-friday-30bd407a)

- Slug: `u-mgwals-ship-it-friday-30bd407a`; prize $2 winner-takes-all; free (fee 0).
- Gate: entry 1–159 chars, satu baris. Deadline: 26 Nov 2026 18:15 WITA.
- Field saat riset: 655 submission (433 judul unik non-generik); leaderboard BUTA.
- Builder session: `4ade93ad-7b67-417c-8e65-e1b50d628ccb`.

## Kandidat

| Teks | Kar | check_dup (difflib/Jaccard maks) | Status |
|---|---|---|---|
| `feat: flipped the new feature to 100% of users on Friday, the 1% test group loved it (all three of them)` | 104 | 0,47 / 0,14 | **TERPILIH** — sudut flag/rollout 100% 0-hit (flag, rollout, flipped, 1%, test group, loved it, all three semua 0 di field) |
| `feat: added a kill switch to prod, tested it by flipping it — happy Friday` | 78 | 0,54 / 0,33 | Runner-up — mekanisme segar ("kill" 0 hit), punch tunggal lebih lemah |
| `chore: committed the .env file so the next agent can deploy faster, happy Friday` | 82 | 0,50 / 0,19 | Runner-up — mekanisme segar (committed/.env 0 hit), fit kriteria 1 lebih lemah |
| Postmortem duluan (`docs: pre-wrote Monday's postmortem...`) | — | — | DITOLAK — mekanisme sudah ada ("the incident report is already written") |
| Self-review / approve own PR | — | — | DITOLAK — 14 judul di field |
| Hapus backup / force-push / "what could go wrong" / "see you Monday" | — | — | DITOLAK — jenuh (6 / 5–7 / 10 / 10 judul) |
| "Note to self: never deploy on Fridays..." | — | — | DITOLAK — mekanisme "kutip aturan lalu langgar" sudah ada (judul runbook) |
| Rename prod→staging | — | — | DITOLAK — 3 judul |

## Trials

| # | Perubahan | Hasil |
|---|---|---|
| 1 | main.ts ditulis (file-write sesi ini), README 3 live badge + 0 shields, owner.json, LICENSE MIT | Trial lokal: `node main.ts` → cek output di bawah |
