# Trading Strategy Backtest

Systematic trading strategy research and backtesting framework.

## Strategy
A couple of signals incorporated for a couple of asset classes

## Performance
| Metric | Value |
|---|---|
| Sharpe Ratio | - |
| CAGR | - |
| Max Drawdown | - |
| Calmar Ratio | - |

## Setup
pip install -r requirements.txt

## Usage
python backtest/engine.py --start 2018-01-01 --end 2024-01-01

## Structure
- `strategy/` — signal generation and portfolio logic
- `backtest/` — engine and performance metrics
- `data/` — raw and processed market data (gitignored)
- `notebooks/` — exploration and prototyping
- `results/` — output charts and CSVs (gitignored)

## Disclaimer
For research purposes only. Not financial advice.