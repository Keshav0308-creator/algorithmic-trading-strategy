# Algorithmic Trading Strategy Simulation

A backtesting framework for rule-based and data-driven trading strategies, built during a virtual internship at Predictive Finance and extended as an independent research project.

---

## What It Does

- Designs and backtests multiple trading strategies on historical equity data
- Evaluates strategies using **risk-adjusted performance metrics**
- Simulates real-time trading environments to assess robustness
- Analyses signal performance across different market conditions
- Documents findings in a co-authored research paper

## Strategies Tested

- **Rule-based:** Moving average crossovers, RSI-based entry/exit signals
- **Data-driven:** Predictive models trained on historical OHLCV data
- **Hybrid:** Combining technical signals with statistical filters

## Performance Metrics Used

| Metric | Purpose |
|---|---|
| Sharpe Ratio | Risk-adjusted return measurement |
| Max Drawdown | Worst peak-to-trough loss |
| Win Rate | % of profitable trades |
| Profit Factor | Gross profit / gross loss |

## Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core logic |
| Pandas | Data handling and signal generation |
| NumPy | Numerical computations |
| Matplotlib | Equity curve and drawdown plots |
| yfinance | Historical market data |

## Key Concepts

- **Backtesting** — simulating strategy performance on historical data
- **Market microstructure** — understanding order flow and price formation
- **Signal validation** — testing robustness across market regimes
- **Risk management** — position sizing and drawdown control

## Project Structure

```
algorithmic-trading-strategy/
│
├── strategy.py         # Core strategy logic and backtesting engine
├── signals.py          # Signal generation (MA, RSI, custom indicators)
├── backtest.py         # Performance evaluation and reporting
├── data/               # Historical price data
├── results/            # Strategy performance outputs
└── README.md
```

## Usage

```python
# Install dependencies
pip install pandas numpy matplotlib yfinance

# Run backtest
python backtest.py
```

---

*Developed during virtual internship at Predictive Finance (Aug 2025 – Jan 2026) and extended independently. Co-authored a research paper documenting strategy findings and market microstructure insights.*
