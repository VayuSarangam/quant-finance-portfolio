# Portfolio Optimization (Mean–Variance / Efficient Frontier)

This project implements Markowitz mean–variance portfolio optimization using historical returns.
It constructs:
- Minimum-variance portfolio
- Efficient frontier (target return sweep)
- Tangency (maximum Sharpe) portfolio
- Portfolio weights + risk/return summary

## Methods
- Compute daily log returns from adjusted close prices
- Annualize mean returns and covariance
- Solve constrained optimization problems:
  - weights sum to 1
  - long-only (w >= 0) baseline
  - optional: max weight cap per asset

## Outputs
- Efficient frontier plot
- Tangency and minimum-variance markers
- Weights tables and summary metrics

## Run in Google Colab
Open notebook:
https://colab.research.google.com/github/VayuSarangam/quant-finance-portfolio/blob/main/portfolio-optimization/Portfolio_Optimization_MeanVariance.ipynb
