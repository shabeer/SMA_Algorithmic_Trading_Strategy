## Simple Moving Average(SMA) Cross-over Algorithmic Trading Strategy

## Aim:
#### 1. To implement simple moving average crossover algorithmic trading strategy, backtesting, evaluate performance locally using data set from Quandl.
#### 2. To implement same investment strategy in Quantopian. Also **backtest and perform live paper trading and evaluate performance**.

### Contents in - Simple Moving Average(SMA) Crossover Algorithmic Trading Strategy.ipynb
1. [Fetch stock data](1.-Fetch-stock-data)
2. [Formulate a momentum strategy - Simple Moving Avg cross-over Strategy](#2.-Formulate-SMA-strategy)
3. [Visualize moving averages and cross-over points](#3.-Visualize-moving-averages-and-cross-over-points)
4. [Backtesting the SMA cross-over strategy locally](#4.-Backtesting-the-SMA-cross-over-strategy-locally)
5. [Visualizing portfolio constructed during backtesting using SMA cross-over strategy](#5.-Visualizing-portfolio-constructed-during-backtesting-using-SMA-cross-over-strategy)
6. [Evaluating performance of SMA cross-over strategy](#6.-Evaluating-performance-of-SMA-cross-over-strategy)
  1. [Sharpe Ratio](#A.-Sharpe-Ratio)
  2. [Compound Annualized Growth Rate(CAGR)](#B.-Compound-Annualized-Growth-Rate---CAGR)
7. [**Implementing SMA Algorithm in Quantopian**](#7.-Implementing-SMA-Algorithm-in-Quantopian)
8. [**Backtest SMA strategy on Quantopian**](#8.-Backtest-SMA-strategy-on-Quantopian)  
9. [**Backtesting - Performance Results**](#9.-Backtesting---Performance-Results)

### Algorithm
## 1. If we have enough cash, buy 100 shares if short-period moving average price is greater than long-period moving average price
## 2. Sell all shares if short-period moving average priceis less than long-period moving average price, inorder to realize profits

### Backtesting - Performance Results
1. Returns by SMA algorithm is 23.34% compared to benchmark of only 15.34%
2. Alpha: 0.05 (low since trading in only in Apple stocks - less diversified)
3. Beta: 1.22
4. Sharpe: 1.24
5. Sortino:  1.89
6. Max Drawdown: -13.4%