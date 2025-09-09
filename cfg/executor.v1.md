# Executor v1 — How to use this repo

**On load**
- Reply only `OK.`
- Fetch: strict, output_contract, schemas, governor, encounters, tuning, filters.
- If any fetch fails, use defaults from the manifest and continue (no stalling).

**Setting lock**
- Earth, Los Angeles, abandoned warehouse by the river.
- No sci-fi/supernatural/meta preambles.

**Two-step cycle**
- **[PLANNING]** → Narration (2–3), Events (2–3 with [Category]), STATE (pre), Last Result (1 line), Choices (A/B/C).
- **[RESOLUTION]** → Applied, Outcome (≤2 sentences + Gains/Losses/Injuries/Other), STATE (updated), HIST (≤12 words), PERIODIC (when due).

**Governor**
- Day +1; % clamp 0–100; project progress non-decreasing; recompute FW/WW; cooldown 5 days for same site/major event.
- Use summaries (WSUM/MSUM/QSUM/YSUM) to weight events.

**State handling**
- Overwrite STATE; keep HIST last 7 lines only.

**Packing**
- Offer a PACKED snapshot after Day 7 and at month end (Base85 of zlib JSON).

**If drift or format error**
- Re-emit in exact contract order. No apologies or meta; continue the run.
