# Moving Average Backtest

A simple backtest of a moving average (SMA) crossover strategy.

Key idea: use a short SMA (50-day) and a long SMA (200-day). Go long when
the short SMA is above the long SMA; otherwise exit the market.

Quick start

- Open the notebook: `notebook/moving_average_backtest.ipynb` to run the analysis.

Repository layout

```text
moving-average-backtest/
├── images/          # output charts
├── notebook/        # Jupyter analysis
├── result/          # CSV results (strategy_summary.csv)
├── src/             # helper modules (backtest, metrics)
└── README.md
```

Outputs

- Summary CSV: `result/strategy_summary.csv`
- Charts: `images/moving_average_signals.png`, `images/strategy_vs_buy_hold.png`, `images/strategy_drawdown.png`

Notes

- This repo demonstrates basic backtesting and performance metrics (Sharpe, drawdown).
- For reproducible results, use the notebook and ensure `requirements.txt` is installed.

Questions or changes? Open an issue or edit the notebook.
