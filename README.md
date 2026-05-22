# S&P 500 & Macroeconomic Analysis (2015–2025)

## Overview
End-to-end analysis of S&P 500 returns and macroeconomic indicators 
using Python and SQL. Pulls live data from FRED and Yahoo Finance, 
stores in SQLite, and runs OLS regression analysis.

## Key Skills Demonstrated
- Python (pandas, numpy, matplotlib, statsmodels)
- SQL (SQLite, JOINs, GROUP BY, CASE statements, aggregate functions)
- Financial data collection via FRED API and Yahoo Finance
- OLS regression analysis
- Data visualization

## Key Findings
- S&P 500 averaged 1.54% monthly returns during high rate environments 
  vs 0.87% during low rate periods
- Unemployment rate is the strongest predictor of monthly returns (p=0.000)
- Federal Funds Rate shows a small positive association with returns (p=0.031)
- Models explain ~10% of total stock market variation, consistent with 
  prior academic literature

## Data Sources
- Federal Reserve Economic Data (FRED)
- Yahoo Finance (via yfinance)

## Files
- analysis.ipynb — Main Jupyter Notebook
- macro_charts.png — Output visualizations
- macro_data.db — SQLite database