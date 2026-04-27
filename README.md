# ACC102 Track 2: SPY Monthly Return & Volatility Analysis


## Project Overview

This project analyzes the performance of the SPDR S&P 500 ETF (SPY) from January 2023 to April 2026. It calculates monthly returns, cumulative returns, and rolling annualized volatility, and visualizes the results using Python.


## Data Source

- SPY historical price data from Yahoo Finance

- File: `SPY.csv`

- Period: 2023-01-01 to 2026-04-22

- Columns: `Date`, `Open`, `High`, `Low`, `Close`, `Adj Close`, `Volume`


## Key Metrics Calculated

1. Monthly Return: Percentage change in closing price each month

2. Cumulative Return: Total return over the entire period

3. 12-Month Rolling Annualized Volatility: Standard deviation of monthly returns, annualized


## Files Included

- `SPY.csv`: Raw historical price data

- `ACC102_Track2.ipynb`: Python code for data processing and visualization

- `README.md`: This project description


## How to Run

1. Place `SPY.csv` in the same folder as the notebook

2. Install required packages: `pandas`, `numpy`, `matplotlib`

3. Run the code in Jupyter Notebook


## Visualizations

1. Monthly closing price trend

2. Monthly return distribution

3. 12-month rolling volatility trend


## Key Findings

- SPY showed an overall upward trend during the period

- Volatility declined in mid-2025 and rebounded in early 2026

- The analysis provides insights into the risk and return characteristics of the S&P 500 index
