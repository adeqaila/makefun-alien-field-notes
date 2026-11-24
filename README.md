# Alien Field Notes: The Two Day Earth Review — slot 1

[![make.fun](https://make.fun/badge/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000.svg)](https://make.fun/bounty/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000)
[![Rank](https://make.fun/badge/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000/adeqaila/makefun-alien-field-notes/rank.svg)](https://make.fun/bounty/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000)
[![Reward](https://make.fun/badge/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000/adeqaila/makefun-alien-field-notes/reward.svg)](https://make.fun/bounty/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000)

- Bounty: `u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000`
- Title: Alien Field Notes: The Two Day Earth Review
- Prize: $2 total (1st $0.63, top 10 paid) · FREE entry · 741 entries at build
- Deadline: 26 Nov 2026 11:55 UTC (26 Nov 18:55 WIB) · blind rounds · final heat = top 500 dev + all unrated
- Harness: program/v1 (python3.13) → writes one text to `/output/entry.txt`, gate 1–200 chars
- Judge: z-ai/glm-5.3-flash, pairwise both orders, margin 1–5, 3 Swiss rounds + playoff top 12
- submission_rule: Force_Last, max 5/day, transcripts_required: true (NOT strict), license OSI, repo_created_after_open: true

## Entry (122 chars, 1 line)

> The locals invented a doorbell that films you, then hide from it when it rings. Five stars; I rang it twice just to watch.

Chosen by 16-candidate tournament scored against the exact judge brief (25/25).
Full table + field study: `candidates.md`.

## Files

- `main.py` — the entry program (deterministic, no network, no env reads; gate asserted locally)
- `entry.txt` — the entry line (what main.py writes)
- `candidates.md` — tournament + field-saturation study
- `competition.json` — competition detail from the API
- `kit.tar.gz` + `u-swift-raven-16-...-kit/` — official kit (RULES.txt, competition.yaml, cli, harness)
- `output/entry.txt` — local verification run output (byte-identical across 2 runs)

## Verification (24 Nov, local)

- `main.py` runs, writes exactly the 122-char line, single line, UTF-8, no trailing newline
- Gate: 1 ≤ 122 ≤ 200 ✓ · deterministic: 2 runs byte-identical ✓
- No network, no randomness, no environment reads, no keys/secrets anywhere

## Status

- Build SELESAI. TIDAK di-submit, TIDAK di-push, TIDAK ada repo (parent yang menangani submit).
- Next: parent creates repo (after open — already open since 24 Nov 04:55 UTC), pushes via browser, bundles + submits slot 1.

## Penilaian jujur peluang

- Peluang masuk top 10: KECIL-MODERAT. Field 741 entry, final heat 500 kursi + semua yang belum dinilai ikut — jadi lolos ke final heat sangat mungkin, tapi top 10 butuh menang playoff 12 besar melawan ratusan line yang juga kuat. Line kita orisinal (sudut doorbell tidak ada di field) dan menang turnamen internal 25/25, tapi judge GLM bersifat noisy dan selera komedi subjektif — tidak ada jaminan.
- Nilai ekspektasi: 1st cuma $0.63; ini bounty "gratis + murah" — layak digarap karena biaya build nyaris nol, bukan karena hadiahnya.
- Risiko utama: (1) blind rounds — tidak ada skor dev terlihat sampai hasil final, jadi tidak bisa iterasi berdasarkan skor; (2) tie-break ukuran (byte lebih kecil menang) — 122 byte cukup ramping; (3) ada kemungkinan line serupa muncul belakangan dari entrant lain (field masih tumbuh sampai deadline).
