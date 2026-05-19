# S&P 500 Multibagger Analysis

## Overview
A Python-based stock screening tool that analyses all 503 S&P 500 companies 
to identify potential multibagger stocks, last week's top gainers/losers, 
and monthly performance trends.

## Key Findings (Latest Run)
- **76 multibagger candidates** identified from 503 stocks screened
- **Top gainer last week:** CSCO (+20.42%)
- **Top loser last week:** INTC (-16.43%)
- **Highest 1Y return:** SNDK (+3,337%)

## Files
- `sp500_multibagger_analysis.ipynb` — Full Python analysis notebook
- `multibagger_candidates.csv` — 76 stocks passing multibagger criteria
- `top_gainers.csv` — Top 10 gainers last week
- `top_losers.csv` — Top 10 losers last week
- `monthly_performance.csv` — Monthly returns of top 10 candidates

## Tools & Techniques
- Python (yfinance, Pandas, NumPy, Matplotlib)
- Live data pulled directly from Yahoo Finance
- Screening criteria: 1Y Return >30%, 1M Return >5%, Max Drawdown >-40%
- Metrics: Cumulative return, volatility, max drawdown
