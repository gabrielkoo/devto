# 📊 gabrielkoo · dev.to Stats Dashboard

An interactive, mobile-friendly dashboard visualising my [dev.to](https://dev.to/gabrielkoo) article analytics — views, reactions, traffic sources, and per-article breakdowns over time.

## 🌐 Live Site

**[gabrielkoo.github.io/devto](https://gabrielkoo.github.io/devto/)**

## Features

- Summary stats (total views, reactions, comments, articles)
- Daily activity bar chart with log scale — switchable between views and reactions
- Stacked chart mode showing top 3 or 5 articles for the selected time window
- Time range filter: 7d / 30d / 90d / 180d / 1y / 2y / All
- Traffic sources donut chart (all-time)
- Top 10 articles ranked by the selected metric and time range, with both views and reactions shown
- Light / dark theme toggle (persists in localStorage)

## Data Source

Data is fetched live from [`devto-stats-github-action`](https://github.com/gabrielkoo/devto-stats-github-action), which updates daily via GitHub Actions.
