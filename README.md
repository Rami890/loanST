# NGO Loan Planner

Interactive 10-year loan repayment planning tool for NGO fundraising committees.

## Features

- **Single scenario** — adjust families, monthly donation, ceiling, and fixed income streams
- **Compare mode** — run three scenarios side by side (A / B / C)
- **Surplus toggle** — switch between cumulative reserve and month-by-month view
- **Timeline table** — shows every transition between surplus and deficit

## How to publish on GitHub Pages

1. Create a new GitHub repository (can be public or private with Pages enabled)
2. Upload `index.html` to the root of the repository
3. Go to **Settings → Pages**
4. Under "Source", select **Deploy from a branch**
5. Choose `main` branch, `/ (root)` folder
6. Click **Save**
7. Your site will be live at `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

## No dependencies to install

The HTML file is fully self-contained. It loads Chart.js and Google Fonts from CDN.
It works offline too if you download Chart.js locally.

## Loan parameters (hard-coded)

| Parameter | Value |
|-----------|-------|
| Loan total | ₪1,000,000 |
| Monthly repayment | ₪12,500 |
| Term | 120 months (10 years) |
| Founding families | 30 |
| Hall rental starts | Month 25 |

To change the founding families' data, edit the `REAL_REMAINING` array in `index.html`.
