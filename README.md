# 💰 Budget Tracker 2026

A fully offline, self-contained expense dashboard. No server needed — just open `index.html` in any browser.

## Features
- 📊 Dashboard with 4 charts (monthly bar, category donut, trend lines, % stacked bar)
- 📋 Month-wise expense sheets (March–December 2026)
- ➕ Add / ✏️ Edit / 🗑 Delete expenses
- 💾 All data stored in browser `localStorage` — persists across sessions
- ⬇️ Export entire tracker to Excel anytime
- ⚠️ Over-budget warnings per month
- 🔍 Search & filter by category and month

## How to host on GitHub Pages

1. Create a new GitHub repository (e.g. `budget-tracker-2026`)
2. Upload `index.html` and `README.md` to the repo root
3. Go to **Settings → Pages**
4. Under **Source**, select `main` branch and `/ (root)` folder
5. Click **Save** — your dashboard will be live at:
   `https://<your-username>.github.io/budget-tracker-2026/`

## Local usage
Just double-click `index.html` — no installation or internet connection required (charts load from CDN on first open).

## Data storage
All data lives in your browser's `localStorage` under the key `budget_tracker_2026`.  
To back up: use the **Export Excel** button anytime.  
To reset: open browser DevTools → Application → Local Storage → delete the key.

## Adding expenses
1. Click any month in the sidebar
2. Fill in Date, Category, Description, Amount, Mode
3. Click **+ Add**

Changes save instantly and persist across browser sessions.
