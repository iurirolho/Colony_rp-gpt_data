# Colony RP GPT Data — Pure TXT (Rev 6.1)
Date: 2025-09-09

This repo is intentionally **pure text** so any GPT can load instructions by opening URLs you paste.

## Start here (one URL)
Paste this single link in chat and say: *Open this and follow it. Begin Day 1 in [PLANNING] after loading.*  
- **Master file:** https://iurirolho.github.io/Colony_rp-gpt_data/txt/00_MASTER.txt

## Or use the full loader (multiple URLs)
Open and follow:  
- **Pages loader:** [/txt/PASTE_ME_PAGES_LOADER.txt](/txt/PASTE_ME_PAGES_LOADER.txt)  
- **Raw loader:** [/txt/PASTE_ME_RAW_LOADER.txt](/txt/PASTE_ME_RAW_LOADER.txt)

## What the Master includes
- STRICT mode (OK-only ack; LA warehouse lock; no meta/UI/URLs)
- OUTPUT CONTRACT (two-step + legend)
- EXECUTOR (step-by-step behavior)
- SCHEMAS (STATE/HIST + summary formats)
- GOVERNOR (rates, invariants, cooldowns)
- ENCOUNTERS + TUNING
- FILTERS (block sci-fi/meta/UI strings)
- COMPAT BOOTSTRAP (offline fallback)
- GUARD SELF-TESTS (to avoid drift)
- STARTER STATE & HIST

## GitHub Pages
If not already enabled: Settings → Pages → Deploy from branch → `main` → `(root)`.  
Site root: https://iurirolho.github.io/Colony_rp-gpt_data/

## Notes
- No JSON required. All configs are plain text.  
- If a model refuses multiple links, just use the **Master** URL.  
- If it prints UI/meta or stalls, the Master includes commands to recover.
