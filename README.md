# S&P 500 Return & Volatility Analysis
ACC102 Track 2 Assignment | XJTLU

## Project Overview
This project analyzes the return, volatility, and risk-adjusted performance of 10 major S&P 500 stocks using WRDS-CRSP monthly data (2023–2024).

## Dataset
- Source: WRDS-CRSP Monthly Stock File
- Period: Jan 2023 – Dec 2024
- Stocks: AAPL, MSFT, GOOGL, AMZN, META, NVDA, JPM, V, PG, JNJ
- Variables: Date, Ticker, Price, Monthly Return, Volatility

## Methodology
- Data cleaning and preprocessing
- Annualized return and volatility calculation
- Sharpe Ratio (risk-adjusted performance)
- Visualization of trends, risk-return relationship, and rankings

## Files
- `acc102_wrds_analysis.ipynb`: Main Python analysis notebook
- `wrds_analysis_result.png`: Generated charts
- `README.md`: Project documentation

## How to Run
1. Install packages: `pandas`, `numpy`, `matplotlib`
2. Run the notebook
3. View printed results and the generated figure

## Key Findings
- Visa (V) shows the highest risk-adjusted return.
- Amazon (AMZN) has the highest volatility.
- Tech stocks have higher risk-return profiles, while consumer/financial stocks are more stable.
