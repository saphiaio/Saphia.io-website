# saphia.io — upload, 20 Oct 2026

## What's in this folder (20 files)
- 9 new market briefs: racehorses, breeding_stallions, rare_whisky_casks, japanese_whisky, champagne, pu_erh_tea, maple_syrup, vintage_guitars, falcons (*_dashboard.html)
- 4 revised briefs: fine_wine, old_masters, rare_books, stamps
- home.html, markets.html, method.html, advisers.html (static pages; counts now fifty, glossary 58 terms)
- _redirects (50 market routes + aliases)
- github.md, UPLOAD-INSTRUCTIONS.md

Also upload the three editing masters from saphia-site/ so the repo stays in step:
Saphia Home.dc.html, Saphia Markets.dc.html, Saphia Method.dc.html.

## Upload (browser method)
1. Open github.com/saphiaio/Saphia.io-website on the main branch.
2. "Add file" → "Upload files".
3. Drag ALL files in this folder (not the folder itself) onto the upload area; GitHub overwrites the existing copies.
4. Commit message: "20 Oct 2026 — nine new markets (50), glossary 58 terms, home/wine refinements". Commit directly to main.

## Verify once deployed
- saphia.io/                       → "Fifty markets →"
- saphia.io/markets                → 50 tiles in each of By grade / By family / A–Z
- saphia.io/method                 → Σ1 3 · Σ2 7 · Σ3 19 · Σ4 19 · Σ5 2; glossary "58 terms"
- saphia.io/falcons-dashboard, /maple-syrup-dashboard, /vintage-guitars-dashboard, /pu-erh-tea-dashboard, /champagne-dashboard, /japanese-whisky-dashboard, /rare-whisky-casks-dashboard, /breeding-stallions-dashboard, /racehorses-dashboard → load
- saphia.io/puerh-dashboard, /falconry-dashboard, /whisky-casks-dashboard → redirect (301)
