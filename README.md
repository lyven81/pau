# Pau Analytics — Storefront

The public website for **Pau Analytics**, a data analytics consultancy for Malaysian business owners. Static site served by GitHub Pages on the custom domain **www.pauanalytics.com** (CNAME in this repo).

Turns the data a business already collects into clear decisions on pricing, customers, stock, and marketing spend. Every engagement ships as a plain-English case study, an interactive dashboard, and an AI assistant.

## Design system — Data Stories Lab (editorial)

Shared look with the [data-analyst portfolio](https://lyven81.github.io/data-analyst-portfolio/), so storefront and case studies read as one brand.

- **Storefront pages** — white paper `#fff`, black ink `#222`, hairlines `#dddddd`, gold accent `#B8860B`, navy for numbers `#1E3A5F`. Font **Arial/Helvetica**, headlines weight 900. Sticky black-ruled masthead with a hamburger drawer on mobile.
- **Case-study pages** — the portfolio's article layout: **Source Serif 4** body + Arial furniture, 2:1 hero, kicker / title / standfirst / dateline, numbered findings.
- **Self-contained** — inline CSS + inline SVG, Google Fonts via CDN, cover/chart images from the portfolio `raw.githubusercontent` URLs. All internal links are **relative**.

## Structure

- **Storefront**: `index`, `services`, `case-studies`, `how-we-work`, `pricing`, `faq`, `about`, `contact` (plus `case-study-template`, `landing`, `privacy`, `thank-you`).
- **15 case-study pages** rebranded from `lyven81/data-analyst-portfolio` into Pau Analytics pages. Their Dashboard / AI Assistant tabs link to the live portfolio instruments.
- **`services.html`** — the 5 services, each with **4 example case studies** in a 2×2 grid (20 unique studies, none repeated across services).
- **`case-studies.html`** — 6 flagship cover-image cards; "Browse the full Data Stories Lab library" → the portfolio index.

## The five services

Pricing & Promotions · Customer Retention & Value · Demand & Inventory Planning · Marketing ROI · Sales & Profit Performance.

## Contact form

Posts via **FormSubmit** to `admin@pauanalytics.com`, then redirects to `thank-you.html` (`_next`). FormSubmit needs a one-time activation click on first submission.

## Deploy

GitHub Pages from `main` (root path). Custom domain **www.pauanalytics.com** via the `CNAME` file (keep it). Because all links are relative, the site also works under a project path.

## Related

- **[lyven81/data-analyst-portfolio](https://github.com/lyven81/data-analyst-portfolio)** — the case-study, dashboard, and AI-assistant library (Data Stories Lab). Source of the rebranded case pages and cover images.
- Source staging: `Documents/02_Pau-Storefronts/pau-analytics/pau-analytics-dsl-site/`.

---

© 2026 Pau Analytics | Data-Driven Solutions
