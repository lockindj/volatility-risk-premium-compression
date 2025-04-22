# volatility-risk-premium-compression
Research notebook investigating whether the volatility risk premium in SPX options has structurally compressed over time.

Key steps:
- Black-Scholes IV calculation (Newton-Raphson + Bisection)
- Realized volatility computed over forward 21-day windows
- Weighted IV aggregation by midprice
- Visualization of IV vs. RV, and VRP compression

 Structure
- `volatility_risk_premium.ipynb` — full research notebook
- `README.md` — this file
