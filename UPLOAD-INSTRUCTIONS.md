# Upload to GitHub — 29 Oct 2026 batch

Files: all of saphia-site/ (upload the folder contents to the repo root, replacing existing files)

## What changed
- New thematic pages: Tax and legal wrappers at /tax (/wrappers, /legal → 301); Auction or dealer at /auction-vs-dealer (/auctions, /dealers, /auction-or-dealer → 301). The set of eleven is complete
- Themes index rebuilt: three groups (Before you buy / While you hold / When you sell) with one-line descriptions, plus a collapsed 51 × 11 coverage grid generated from the dashboard footnotes
- All 51 dashboards: snapshot footnote now lists every theme covering the market, including Tax and Auction or dealer
- Mobile: every table on every page is now inside a horizontal-scroll wrapper (12 dashboards fixed)
- Maple Syrup and Vanilla: repaired malformed citation links in the Exit depth block (maple's missing source 12 removed)
- Earlier in this batch: Climate, Access, Custody, Sanctions, Provenance, Who sets the price, Exit depth, Substitutes; /about and /themes pages; nav is About / Methodology / Markets / Themes everywhere; Method renamed Methodology; Markets "Recently updated" row

- New /report page (report.html): report builder — reads any brief and its themes client-side, prints to PDF. Linked from every brief and from Markets.

## Verify once deployed
- saphia.io/themes → three groups, eleven themes; "Which themes cover a market" opens to a 51-row grid
- saphia.io/tax and saphia.io/auction-vs-dealer → load, 8 sections each, 51-row registers; auction page sources numbered 20–34
- saphia.io/gold-dashboard → footnote lists Exit depth … Auction or dealer · Tokenising scarce assets
- any dashboard on a phone → tables scroll sideways, nothing overflows the page
- saphia.io/wrappers, /auctions → redirect

---

# saphia.io — upload, 27 Oct 2026 (9 files)

Drag onto github.com/saphiaio/Saphia.io-website (main) → Add file → Upload files. Commit directly to main.

Files: tokenisation.html (new), method.html, _redirects, gold_dashboard.html, fine_wine_dashboard.html, polished_diamonds_dashboard.html, coloured_gemstones_dashboard.html, art_dashboard.html

## What changed
- New thematic pages: Tax and legal wrappers at /tax (/wrappers, /legal → 301); Auction or dealer at /auction-vs-dealer (/auctions, /dealers, /auction-or-dealer → 301). The set of eleven is complete
- All dashboards link to Tax and Auction or dealer in the footnote
- New thematic pages: Climate and supply shock at /climate; Fractional and fund access at /access (/funds, /fractional → 301)
- All dashboards link to Access in the footnote; 27 also link to Climate
- New thematic pages: Storage, custody and insurance at /custody (/storage → 301); Sanctions, tariffs and origin at /sanctions (/tariffs → 301)
- All dashboards link to Custody in the footnote; 27 also link to Sanctions
- New thematic pages: Provenance and verification at /provenance; Who sets the price at /price-setters (/who-sets-the-price → 301)
- All dashboards: snapshot footnote now reads "Read across markets in: …" listing every theme that covers the market
- Navigation on every page is now About / Methodology / Markets / Themes
- New /about page (copy from the home page sections plus contact details); /about no longer redirects to /method
- New /themes index page listing all thematic pages
- Contact removed from the nav; the page stays live at /contact and is linked from /about
- New thematic page: Tokenising scarce assets, at /tokenisation (plus /tokenization → 301)
- Method: "Thematic pages" section added below Holding horizon and exit depth, linking the theme
- Five dashboards (Gold, Fine Wine, Polished Diamonds, Coloured Gemstones, Art): one-line cross-link appended to the snapshot footnote

## Verify once deployed
- saphia.io/tax and saphia.io/auction-vs-dealer → load, 8 sections each, 51-row registers
- saphia.io/themes → eleven themes; "in preparation" line gone
- saphia.io/climate → 25-row register (27 markets); saphia.io/access → 51-row register
- saphia.io/themes → nine themes
- saphia.io/custody → 51-row register; saphia.io/sanctions → 27-row register
- saphia.io/themes → seven themes
- saphia.io/provenance and saphia.io/price-setters → load, 8 sections each, 51-row registers
- saphia.io/themes → five themes
- saphia.io/about → loads with four sections; saphia.io/themes → three themes
- any dashboard → nav reads About / Methodology / Markets / Themes
- saphia.io/tokenisation → loads, 7 sections, 20 sources, table III column reads "Conditions met"
- saphia.io/method#themes → section present, link works
- saphia.io/gold-dashboard → snapshot footnote ends "Tokenising scarce assets →"

---
# saphia.io — afternoon upload, 20 Oct 2026 (16 files)

Drag every file in this folder onto github.com/saphiaio/Saphia.io-website (main) → Add file → Upload files. Commit directly to main.
Then DELETE natural_diamonds_dashboard.html from the repo (its URL redirects to Polished Diamonds).

## What changed
- New thematic pages: Tax and legal wrappers at /tax (/wrappers, /legal → 301); Auction or dealer at /auction-vs-dealer (/auctions, /dealers, /auction-or-dealer → 301). The set of eleven is complete
- All dashboards link to Tax and Auction or dealer in the footnote
- New thematic pages: Climate and supply shock at /climate; Fractional and fund access at /access (/funds, /fractional → 301)
- All dashboards link to Access in the footnote; 27 also link to Climate
- New thematic pages: Storage, custody and insurance at /custody (/storage → 301); Sanctions, tariffs and origin at /sanctions (/tariffs → 301)
- All dashboards link to Custody in the footnote; 27 also link to Sanctions
- New thematic pages: Provenance and verification at /provenance; Who sets the price at /price-setters (/who-sets-the-price → 301)
- All dashboards: snapshot footnote now reads "Read across markets in: …" listing every theme that covers the market
- Navigation on every page is now About / Methodology / Markets / Themes
- New /about page (copy from the home page sections plus contact details); /about no longer redirects to /method
- New /themes index page listing all thematic pages
- Contact removed from the nav; the page stays live at /contact and is linked from /about
- Lab-Grown Diamonds restructured into Part A · Rough (II–V) and Part B · Polished (VI–VIII); rough-price strip added to §III
- Natural Diamonds split into Rough Diamonds (Σ4) and Polished Diamonds (Σ3); 51 markets
- Advisers: four use-case tiles kept, five granular scenarios added under "In practice"
- Fine Wine §IV moved into Champagne as "Houses and the appellation"; sources renumbered on both
- Glossary 58 → 63 terms (sight, tender, polish-grade, country of cutting, natural premium)
- Signed Jewellery cross-link repointed to Polished Diamonds
- Markets: new "Compare" tab — all 51 markets scored 1–5 on Supply, Liquidity, Scarcity, Provenance (steps 1, 4, 5, 6 of the Method sequence); column headers rank by axis

## Verify once deployed
- saphia.io/tax and saphia.io/auction-vs-dealer → load, 8 sections each, 51-row registers
- saphia.io/themes → eleven themes; "in preparation" line gone
- saphia.io/climate → 25-row register (27 markets); saphia.io/access → 51-row register
- saphia.io/themes → nine themes
- saphia.io/custody → 51-row register; saphia.io/sanctions → 27-row register
- saphia.io/themes → seven themes
- saphia.io/provenance and saphia.io/price-setters → load, 8 sections each, 51-row registers
- saphia.io/themes → five themes
- saphia.io/about → loads with four sections; saphia.io/themes → three themes
- any dashboard → nav reads About / Methodology / Markets / Themes
- saphia.io/lab-grown-diamonds-dashboard → two part banners; contents list shows Part A / Part B
- saphia.io/                        → headline, one-line description, three entry links (Markets / Themes / Method)
- saphia.io/report?market=falcons → Falcons brief parts listed, preview renders, Save as PDF opens print
- saphia.io/sitemap.xml and /robots.txt → resolve as plain text
- any dashboard → "Themes that cover this market" block above the footer; on a phone, tables show "Scroll for more →"
- saphia.io/markets                 → 51 tiles in each view; Rough under Σ4, Polished under Σ3
- saphia.io/markets?view=compare    → four-column dot table, 51 rows; clicking "Liquidity" ranks Gold/Silver/PGM/Copper/Oil & Gas/Coffee/Cocoa at five marks
- saphia.io/method                  → Σ4 count 20; glossary "63 terms"
- saphia.io/rough-diamonds-dashboard, /polished-diamonds-dashboard → load
- saphia.io/natural-diamonds-dashboard → 301 to Polished
- saphia.io/champagne-dashboard → 7 sections, 21 sources; /fine-wine-dashboard → §IV pointer, 61 sources
