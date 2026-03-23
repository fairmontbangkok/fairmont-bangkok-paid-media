# Google Ads Budget Dashboard
### ฿100,000 / Month · Generic Keywords · SG · AU · HK · MY

A clean, interactive budget allocation dashboard for Google Ads non-brand keyword planning across Asia & Pacific markets. Built with HTML, CSS, and Chart.js — no frameworks or dependencies required.

---

## Live Demo

🔗 **[View Dashboard](https://your-username.github.io/your-repo-name/)**

> Replace the link above with your actual GitHub Pages URL after deployment.

---

## What's Inside

This dashboard helps you visualise and plan a ฿100,000/month Google Ads budget across four target markets:

| Market | Allocation | Best Keyword | Avg CPC |
|--------|-----------|--------------|---------|
| 🇭🇰 Hong Kong | ฿25,000 | sukhumvit 20 hotel | ฿27.81 |
| 🇲🇾 Malaysia | ฿25,000 | sukhumvit 20 hotel | ฿27.81 |
| 🇸🇬 Singapore | ฿25,000 | best place to stay in bangkok | ฿44.74 |
| 🇦🇺 Australia | ฿25,000 | best place to stay in bangkok | ฿44.74 |

---

## Features

- **Overview tab** — KPI summary cards, market allocation donut chart, CPC comparison, and 30-day budget runway simulation
- **Keyword plan tab** — Full keyword breakdown table with competition level, monthly cost, allocated budget, coverage %, and status pills
- **Recommendations tab** — Priority action list, suggested budget redistribution, and budget tier scenarios (฿100K → ฿1M+)
- **Responsive layout** — Works on desktop and tablet
- **No backend required** — Pure HTML/CSS/JS, runs entirely in the browser

---

## Data Source

All keyword data is sourced from **Google Ads Keyword Planner** (`Book1.xlsx`), Non-Brand campaign targeting Bangkok hotel keywords.

- Campaign type: Non-Brand (Generic)
- Match type: Exact
- Budget estimates: `Avg CPC × Est. Daily Searches × 30 days`
- Currency: Thai Baht (฿)

---

## How to Deploy on GitHub Pages

### Step 1 — Clone or download this repo

```bash
git clone https://github.com/your-username/your-repo-name.git
```

### Step 2 — Make sure `index.html` is in the root folder

The main dashboard file must be named `index.html` at the root of the repository.

```
your-repo/
├── index.html        ← main dashboard file
└── README.md         ← this file
```

### Step 3 — Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages** (in the left sidebar)
3. Under **Branch**, select `main` and folder `/ (root)`
4. Click **Save**
5. Wait 1–2 minutes, then your site will be live at:

```
https://your-username.github.io/your-repo-name/
```

---

## How to Update the Dashboard

All data is hardcoded in `index.html`. To update figures:

1. Open `index.html` in any text editor (VS Code recommended)
2. Search for the section you want to update (e.g. `฿25,000`, `27.81`, market names)
3. Edit the values directly
4. Save and push to GitHub — the live site updates automatically within a few minutes

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| HTML5 / CSS3 | Layout and styling |
| [Chart.js 4.4.1](https://www.chartjs.org/) | Charts and data visualisation |
| [Montserrat](https://fonts.google.com/specimen/Montserrat) | Typography (Google Fonts) |
| [DM Mono](https://fonts.google.com/specimen/DM+Mono) | Monospace labels and numbers |
| GitHub Pages | Free static site hosting |

---

## Key Findings

> **Budget constraint:** At ฿100,000/month, only niche long-tail keywords (33 daily searches) are affordable. Every head-term keyword with 328+ daily searches costs ฿235K–฿620K/month per market — exceeding the entire budget.

**Recommended budget split (skewed for efficiency):**

```
HK  ฿40,000  ──────────────────────────── 40%
MY  ฿40,000  ──────────────────────────── 40%
SG  ฿15,000  ────────                     15%
AU   ฿5,000  ──                            5%
```

To unlock full generic keyword coverage across all 4 markets, a budget of **฿1,000,000+/month** is recommended.

---

## License

For internal planning use only. Data based on estimated Google Ads Keyword Planner values — actual performance may vary.

---

*Generated from Book1.xlsx · Google Ads Keyword Planner · Non-Brand Campaign · Hotel in Bangkok*
