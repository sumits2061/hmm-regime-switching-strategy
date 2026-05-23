# HMM Regime-Switching Quant Strategy

## Project Overview
This project implements a Hidden Markov Model (HMM)-based market regime detection and dynamic portfolio allocation strategy using real financial market data.

The model identifies latent market regimes such as:
- Bull Market
- Bear Market
- Crisis Regime

The strategy dynamically adjusts portfolio exposure based on detected market conditions and evaluates performance using institutional risk-adjusted metrics.

---

## Features
- Hidden Markov Model (HMM) regime detection
- Real market data using Yahoo Finance
- Dynamic portfolio allocation
- Transaction-cost-aware backtesting
- Benchmark comparison
- Risk-adjusted performance analytics
- Sharpe Ratio
- Sortino Ratio
- Maximum Drawdown
- CAGR analysis

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- hmmlearn
- Yahoo Finance API

---

## Strategy Logic

| Regime | Portfolio Allocation |
|--------|----------------------|
| Bull Market | 90% Equity |
| Bear Market | 50% Equity |
| Crisis | 10% Equity |

The model dynamically adjusts exposure according to detected market conditions.

---

## Performance Metrics
The project evaluates:
- Cumulative Return
- CAGR
- Annualized Volatility
- Sharpe Ratio
- Sortino Ratio
- Maximum Drawdown

---

## Future Improvements
- Walk-forward validation
- Online regime updating
- Multi-asset optimization
- Macro-economic feature integration
- Bayesian HMM implementation

---

## Disclaimer
This project is developed for educational and research purposes only and does not constitute financial advice.