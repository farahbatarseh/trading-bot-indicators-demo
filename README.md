# Trading Bot with Technical Indicators (Demo)

This is a simplified **demo project** showing how I structure a Python trading bot using technical indicators such as **EMA**, **RSI**, and **Bollinger Bands**.

> ⚠️ This repository uses **dummy/sample data** and simplified logic.  
> It is **not** my live trading system and it is not intended for real-money trading.

## What this demo shows

- Clean Python structure for:
  - Loading OHLCV data (CSV or generated)
  - Calculating EMA, RSI and Bollinger Bands
  - Generating buy / sell / flat signals
  - Simple backtest loop over historical data
- Focus on **readable code** and **clear separation** of:
  - data loading
  - indicator calculation
  - signal generation
  - backtest/evaluation

## Tech stack

- Python 3.x  
- NumPy, Pandas  
- (Optionally) Matplotlib for plotting equity curves

## Why this repo exists

I use this project as a **public example** of how I write trading-related code for clients:

- modular
- well commented
- easy to extend
- focused on transparency and testing

My full reinforcement learning trading systems (TD3/SAC, custom environments, hybrid replay buffers, MT5 execution, etc.) are **private**, but they follow similar principles of structure and clarity.
