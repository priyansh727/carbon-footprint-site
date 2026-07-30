# Carbon Footprint Site

Static, single-file HTML/CSS/JS site — no build step, no backend. Open `index.html` in a browser, or serve the folder as a static site (works out of the box on GitHub Pages, Netlify, Vercel, etc.). All user data is stored in the browser's `localStorage`.

## Pages

- **index.html** — Landing page linking to everything else.
- **carbon-report.html** — Research & module plan report: Scope 1/2/3 framework, audit of the current SystemETA module, proposed 8-module app, AI roadmap, and 3-phase build plan.
- **carbon-mvp.html** — Working Phase 1 + 2 prototype: org/site setup, Scope 1/2/3 activity engine, supplier questionnaire portal, CSV import + simulated ERP sync, and BRSR Core / GHG Protocol report exports.
- **carbon-ledger.html** — Personal everyday carbon tracker (transport, home energy, food, goods & waste) with a 14-day trend and benchmark gauge.
- **foodprint.html** — Food-only carbon tracker with a 14-day trend, food-group breakdown, and daily swap suggestions.

## Local preview

Any of the following works:

```bash
# just open the file
start index.html

# or serve locally
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to GitHub Pages

Repository Settings → Pages → Source: **Deploy from a branch** → Branch: `master` (root). The live URL will be `https://<user>.github.io/carbon-footprint-site/`.

## Credit

Prepared by Priyansh, Intern — VSQC · July 2026.
