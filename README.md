# Colony RP GPT Data — Pure TXT (Rev 6.1)
Date: 2025-09-09

This repo is intentionally **pure text** so any GPT can load instructions by opening URLs you paste.

## Start here (one URL)
Paste this single link in chat and say: *Open this and follow it. Begin Day 1 in [PLANNING] after loading.*  
- **Master file:** https://iurirolho.github.io/Colony_rp-gpt_data/txt/00_MASTER.txt

---

## Direct TXT modules

### Master (all-in-one)
- Pages: https://iurirolho.github.io/Colony_rp-gpt_data/txt/00_MASTER.txt  
- Raw:   https://raw.githubusercontent.com/iurirolho/Colony_rp-gpt_data/main/txt/00_MASTER.txt  

### Modules
- 01_STRICT.txt  
  Pages: https://iurirolho.github.io/Colony_rp-gpt_data/txt/01_STRICT.txt  
  Raw:   https://raw.githubusercontent.com/iurirolho/Colony_rp-gpt_data/main/txt/01_STRICT.txt  

- 02_OUTPUT_CONTRACT.txt  
  Pages: https://iurirolho.github.io/Colony_rp-gpt_data/txt/02_OUTPUT_CONTRACT.txt  
  Raw:   https://raw.githubusercontent.com/iurirolho/Colony_rp-gpt_data/main/txt/02_OUTPUT_CONTRACT.txt  

- 03_EXECUTOR.txt  
  Pages: https://iurirolho.github.io/Colony_rp-gpt_data/txt/03_EXECUTOR.txt  
  Raw:   https://raw.githubusercontent.com/iurirolho/Colony_rp-gpt_data/main/txt/03_EXECUTOR.txt  

- 04_SCHEMAS.txt  
  Pages: https://iurirolho.github.io/Colony_rp-gpt_data/txt/04_SCHEMAS.txt  
  Raw:   https://raw.githubusercontent.com/iurirolho/Colony_rp-gpt_data/main/txt/04_SCHEMAS.txt  

- 05_GOVERNOR.txt  
  Pages: https://iurirolho.github.io/Colony_rp-gpt_data/txt/05_GOVERNOR.txt  
  Raw:   https://raw.githubusercontent.com/iurirolho/Colony_rp-gpt_data/main/txt/05_GOVERNOR.txt  

- 06_ENCOUNTERS.txt  
  Pages: https://iurirolho.github.io/Colony_rp-gpt_data/txt/06_ENCOUNTERS.txt  
  Raw:   https://raw.githubusercontent.com/iurirolho/Colony_rp-gpt_data/main/txt/06_ENCOUNTERS.txt  

- 07_TUNING.txt  
  Pages: https://iurirolho.github.io/Colony_rp-gpt_data/txt/07_TUNING.txt  
  Raw:   https://raw.githubusercontent.com/iurirolho/Colony_rp-gpt_data/main/txt/07_TUNING.txt  

- 08_FILTERS.txt  
  Pages: https://iurirolho.github.io/Colony_rp-gpt_data/txt/08_FILTERS.txt  
  Raw:   https://raw.githubusercontent.com/iurirolho/Colony_rp-gpt_data/main/txt/08_FILTERS.txt  

- 09_COMPAT.txt  
  Pages: https://iurirolho.github.io/Colony_rp-gpt_data/txt/09_COMPAT.txt  
  Raw:   https://raw.githubusercontent.com/iurirolho/Colony_rp-gpt_data/main/txt/09_COMPAT.txt  

- 10_GUARD_TESTS.txt  
  Pages: https://iurirolho.github.io/Colony_rp-gpt_data/txt/10_GUARD_TESTS.txt  
  Raw:   https://raw.githubusercontent.com/iurirolho/Colony_rp-gpt_data/main/txt/10_GUARD_TESTS.txt  

- 11_STARTER_STATE.txt  
  Pages: https://iurirolho.github.io/Colony_rp-gpt_data/txt/11_STARTER_STATE.txt  
  Raw:   https://raw.githubusercontent.com/iurirolho/Colony_rp-gpt_data/main/txt/11_STARTER_STATE.txt  

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

## Notes
- No JSON required. All configs are plain text.  
- If a model refuses multiple links, just use the **Master** URL.  
- If it prints UI/meta or stalls, the Master includes commands to recover.
