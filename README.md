# S&P 500 & Macroeconomic Analysis (2015–2025)

## Overview
End-to-end analysis of S&P 500 returns and macroeconomic indicators 
using Python and SQL. Pulls data from FRED and Yahoo Finance, 
stores in SQLite, and runs OLS regression analysis.

## Key Skills Demonstrated
- Python (pandas, matplotlib, statsmodels)
- SQL (SQLite, JOINs, GROUP BY, CASE statements, aggregate functions)
- Financial data collection via FRED API and Yahoo Finance
- OLS regression analysis
- Data visualization

## Key Findings
- S&P 500 averaged 1.54% monthly returns during high rate environments 
  vs 0.87% during low rate periods
- Unemployment rate has the strongest association with monthly returns (p<0.001)
- Federal Funds Rate shows a small positive association with returns (p=0.031)
- Model explains 10.6% of S&P500 sample variation, consistent with 
  my prior research

## Data Sources
- Federal Reserve Economic Data (FRED)
- Yahoo Finance (via yfinance)

## Files
- analysis.ipynb — Main Jupyter Notebook
- macro_charts.png — Output visualizations
- macro_data.db — SQLite database
