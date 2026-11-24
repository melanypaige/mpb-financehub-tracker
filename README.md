# FINANCE HUB

A private, browser-only finance and sales tracker: budgets, income, expenses, recurring payments, debts, savings goals, a sales register with verification, employee and platform analytics, and monthly/weekly reports.

**No server, no database, no stored data.** Everything lives in the open browser tab. Use **Export all (CSV)** before leaving and **Import CSV** next time. See `manual.html` for the full guide.

## Two modes
- **Single-user (default):** `config.js` is empty. Nothing is stored; use CSV export/import.
- **Shared (you + a teammate):** fill in `config.js` (public Apps Script URL and Google Client ID). Everyone signs in with Google and shares one private Google Sheet. Setup: `SYNC-SETUP.md` (kept out of the repo, with `Code.gs`).

## Publish with GitHub Pages
1. Create a public repository and upload `index.html`, `manual.html`, `config.js` and `README.md`.
2. Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.
3. Your site appears at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

## Privacy
Your financial data is never part of this repository. **Do not commit exported CSV files.**

Charts use Chart.js loaded from a CDN, so an internet connection is needed to view charts.
