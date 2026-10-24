# The Perfect Trade

Live confluence checklist, trade history and performance dashboard for Set & Forget swing traders.
One static page (`index.html`), no build step, no server. Languages: English, Español, Português (Brasil).

## Pages
- **Checklist**: Weekly, Daily, 4H, 2H/1H/30m, Entry Signal, Stop Loss & Take Profit. Each item asks a Yes/No question with an example chart. Rules check gives TAKE IT or WAIT.
- **Save Trade**: after the checklist, Save trade opens a form (pair, long/short, account balance, entry, stop loss, take profit, risk %, auto lot size, notes, before-trade chart image). Saving sends you to the Dashboard.
- **History**: every saved trade with its plan and chart. Set Win / Loss / Pending when it closes; the $ result fills in from the plan and you can edit it.
- **Dashboard**: net P&L, win rate, profit factor, average confluence, largest win/loss, best streak, trading calendar with weekly summary, long vs short win rate, recent trades.

Data is stored in the browser (localStorage). It stays on that device and browser only.

## Put it live on GitHub Pages
1. Create a new public repo on GitHub, for example `perfect-trade`.
2. Upload `index.html`, `README.md` and `.nojekyll` to the repo root (Add file → Upload files → Commit).
3. Repo **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder `/ (root)` → Save.
4. Wait about 1 minute. The site is live at `https://<your-username>.github.io/perfect-trade/`.

Direct links: `.../perfect-trade/#history` and `.../perfect-trade/#dashboard`.

Educational tool, not financial advice.
