# Credit Spread Valuation Model

An interactive write-up of a credit spread valuation model I built in Excel for the KSU Student Managed Investment Fund (Fixed Income).

**Live site:** https://sagesamcoder23.github.io/credit-spread-model/

## What it does

- Compares investment grade, BBB, A and high yield option-adjusted spreads with their own history (z-score and percentile rank).
- Backtests whether CHEAP and RICH readings were followed by LQD beating or trailing duration-matched IEF over the next 63 trading days.
- Stress-tests the result across 16 lookback and threshold settings and a first-half versus second-half split.

## Data note

This repo contains no raw market data. The model's inputs come from Bloomberg and are not republished. The site shows only statistics and results derived from them: z-scores, percentiles, signal states, and backtest and robustness results.

## Files

- `index.html` is the whole site. Data is embedded, so there is no server or build step.
- `assets/chart.umd.js` is Chart.js 4.4.1 (MIT license), included so the page works without a CDN.

## Built with

Excel (13 sheets, formulas only on the dashboard), VBA snapshot macro, Bloomberg BDH, FRED.

Personal project page. Not an official Kennesaw State University publication. Not investment advice.
