# Trading Strategy Backtest

Systematic trading strategy research and backtesting framework.

## Strategy
AUD/CAD spread mean reversion — exploiting the cointegration between ASX 200 and TSX Composite indices, both driven by commodity-exporting economies.

## Performance
| Metric | Value |
|---|---|
| Sharpe Ratio | - |
| CAGR | - |
| Max Drawdown | - |
| Calmar Ratio | - |

## Data
- ASX 200 (`^AXJO`) and TSX Composite (`^GSPTSE`) equity indices
- AUD/USD and CAD/USD FX rates
- Source: Yahoo Finance via `yfinance` (free, no API key required)

## Setup
pip install -r requirements.txt

## Usage
python backtest/engine.py --start 2000-01-01

## Structure
- `strategy/` — signal generation and portfolio logic
- `backtest/` — engine and performance metrics
- `data/` — raw and processed market data (gitignored)
- `notebooks/` — exploration and prototyping
- `results/` — output charts and CSVs (gitignored)

## Disclaimer
For research purposes only. Not financial advice.