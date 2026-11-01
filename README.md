# Hi, I'm Claire 👋

I build transparent, data-driven tools for business decisions, from staffing and quality control to markets and macroeconomics. Each project states its assumptions, tests its claims with the right statistics, and ships with tests, CI and, where it helps, a live app.

## Projects

**Operations and machine learning**

- **[Labor Optimization](https://github.com/Clairechen163/Labor-Optimization)** ([live app](https://labor-optimization.streamlit.app)): forecasts hourly demand, converts it into staffing needs and solves the cheapest weekly roster as a mixed-integer program, then evaluates changes with randomized experiments and difference-in-differences. On simulated data for a casino, a factory and a retail store, optimized rosters cost 5–26% less than fixed shifts.
- **[Visual Defect Inspection](https://github.com/Clairechen163/visual-defect-inspection)**: flags scratched, discolored and chipped parts using OpenCV rules plus softmax regression and a neural network written from scratch in NumPy, compared with corrected cross-validation tests and priced with a cost-based decision rule. 96% accuracy with no good parts rejected on held-out simulated images.
- **[Restaurant Expansion](https://github.com/Clairechen163/restaurant-expansion)** ([live app](https://restaurant-expansion.streamlit.app)): ranks candidate cities for a new outlet with linear regression (normal equation and gradient descent from scratch), cross-validation and prediction intervals, checked on U.S. Census data.

**Markets and economics**

- **[US Labor, Inflation & AI](https://github.com/Clairechen163/labor-inflation-ai)** ([live app](https://labor-inflation-ai.streamlit.app)): asks whether wage growth predicts US inflation and whether AI shows up in hiring data, using FRED data, Granger tests, Phillips-curve regression and a leakage-free walk-forward backtest. Wage growth is significant in sample but does not reliably improve forecasts.
- **[Stock Signal Lab](https://github.com/Clairechen163/stock-signal-lab)**: tests popular sell signals, trading rules and next-day forecasts with walk-forward validation, block bootstrap and false-discovery-rate control. Only 1 of 33 sell-signal tests survived.
- **[US Market Monitor](https://github.com/Clairechen163/us-market-monitor)**: a daily GitHub Actions monitor that scores U.S. stocks on price, volume, trend and breakouts, plus a weekly test of whether the score predicts returns against the S&P 500.

## Focus areas

Statistical inference and experiment design · forecasting with time-series validation · optimization (linear and integer programming) · machine learning from first principles · reproducible data pipelines

## Tech

Python · NumPy · pandas · SciPy · statsmodels · scikit-learn · PuLP · OpenCV · SQL (SQLite) · Streamlit · Plotly · matplotlib · yfinance · FRED API · GitHub Actions · pytest

## Contact

[Email](mailto:clairechen163@gmail.com)
