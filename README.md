# Portfolio Optimization

## Introduction

The goal of this project was to create multiple models/functions that could:
- Get 5 random stocks from the S&P 500
- Create an efficient portfolio based off daily returns
- Return a portfolio with maximized returns based off user inputs

## Project Sections
- Get a constantly updated list of the stocks inside the S&P 500
- Get 5 random stocks from the S&P 500
- Run statistical analysis
- Visual Representation of data and analysis
- Model an efficient frontier
- Output an efficient portfolio
- Intake user input
- Output optimal portfolio (with pricing) under user constraints

## Results

Took 5 random stock from the S&P500 and ran analysis to see the simple return, the average daily return, and the correlation and variances between the stocks.
Then created a function where a user can input his portfolio value, his risk appetite (measured as volatility), and the list of 5 tickers he wants to invest in.
The function then calculates the portfolio that maximizes returns for his risk appetite.
The function then outputs the weights for each stock in the optimized portfolio, and the amount of shares needed to buy based off the closing price of the last trading day in our date range

## Note on Timeframe
Important to note that we did this analysis on the market **PRE-pandemic**. The market post pandemic is completely different.
