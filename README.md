# X0PA AI — SEO Intelligence Reports

Private client reporting platform for X0PA AI. Served via GitHub Pages at `theprojectseo.github.io/x0pa-ai/`.

## Structure

```
/
├── index.html          — report listing (access-code gated)
├── 2026-04/            — April 2026 report (Jan – Mar 2026 period)
│   └── index.html
└── robots.txt          — Disallow all (noindex)
```

## Adding a new monthly report

1. Copy the latest `YYYY-MM/` folder → rename to new month
2. Update data in `index.html` (KPIs, charts, tables)
3. Add link to root `index.html` report list
4. Commit + push → GitHub Pages rebuilds automatically

## Access

Reports are gated by a client-side access code. Code is shared with the client separately. All pages carry `<meta name="robots" content="noindex, nofollow">` and the root `robots.txt` blocks crawlers — no content should appear in search engines.

## Data sources per report

- Google Search Console
- Ahrefs Site Explorer + Brand Radar
- Microsoft Clarity
- Google Lighthouse (via DataForSEO)
- Freshsales CRM (read-only)

## Prepared by

TheProjectSEO · aditya@theprojectseo.com
