# Colony Survival Sim — GitHub Pages Starter

This repo hosts a **prompt manifest** for a text-based, endless survival simulation inspired by Discovery’s *The Colony (2009–2010)*.

## How to publish

1) In GitHub, create a repo (any name).  
2) Add these files.  
3) Enable **GitHub Pages** → **Deploy from branch** → **/ (root)**.  
4) Your site will be available at: `https://<your-username>.github.io/<repo>/`

## Quick use (in ChatGPT)

Say:  
> Load manifest from: `https://<your-username>.github.io/<repo>/manifest/v1.json`  
> Use its schemas, governor, encounters, tuning, and sample packs.

## Structure

- `.nojekyll` — serve files as-is  
- `.well-known/colony.json` — canonical pointer to the current manifest  
- `manifest/v1.json` — manifest directory (relative links to configs)  
- `cfg/schemas.v1.json` — STATE/HIST/WSUM/MSUM/QSUM/YSUM formats  
- `cfg/governor.v1.json` — invariants, rates, cooldowns, choice rules  
- `cfg/encounter.v1.json` — categories, weights, sites, tags  
- `cfg/tuning.v1.json` — season & summary-driven weights  
- `cfg/packs/sample_state.b85` — packed example STATE+HIST (zlib→Base85)  

## Notes

- All files are **public guidance**. Do **not** store secrets here.  
- You can version configs as `*.v2.json`, update manifest to point to them.  
- For larger archives, split by quarter/month and store in `cfg/packs/`.
