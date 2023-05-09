# Cryptostock Analytica

## Table of Contents

- [Project Overview](#project-overview)
- [Installation and Usage](#installation-and-usage)
- [Example](#example)
- [Results and Summary](#results-and-summary)
- [Analysis](#analysis)
  - [Correlation Analysis](#correlation-analysis)
  - [Technical Analysis](#technical-analysis)
  - [Risk Analysis](#risk-analysis)
- [Conclusion](#conclusion)

## Project Overview

Cryptostock Analytica is a data analysis and visualization project that focuses on the relationship between selected cryptocurrencies and stocks. It utilizes correlation analysis, technical analysis (Simple Moving Averages, Relative Strength Index, and Bollinger Bands), and risk analysis (Standard Deviation and Value at Risk).

## Installation and Usage

1. Install the required libraries:

```bash
pip install pandas numpy yfinance hvplot holoviews requests
```

2. Clone the repository or download the Python script:

```bash
git clone https://github.com/yourusername/cryptostock-analytica.git
```

3. Run the code, and follow the prompts to input the stock symbol and cryptocurrency name.

```bash
python cryptostock_analytica.py
```

## Example

1. Enter the stock symbol for analysis: MSFT

2. Enter the cryptocurrency name for analysis: Bitcoin

3. The program will fetch historical price data for Microsoft (MSFT) and Bitcoin and perform various analyses, producing visualizations for each analysis.

## Results and Summary

The analysis and visualizations will provide insight into the correlation, technical indicators, and risk associated with the selected cryptocurrency and stock. The output will include a scatter plot, line plots for Simple Moving Averages, Relative Strength Index, Bollinger Bands, and bar plots for Standard Deviation and Value at Risk.

## Analysis

### Correlation Analysis

The program calculates the Pearson correlation coefficient between the price of the selected cryptocurrency and the selected stock. A scatter plot is displayed to visualize the relationship between the two assets. The correlation coefficient is interpreted as weak, moderate, or strong (positive or negative) correlation.

### Technical Analysis

The program performs technical analysis on the selected cryptocurrency and stock using three popular technical indicators:

1. **Simple Moving Averages (SMA)**: The program calculates the 30-day and 100-day SMAs for both the cryptocurrency and stock, providing insight into their price trends.

2. **Relative Strength Index (RSI)**: The program calculates the 14-day RSI for both the cryptocurrency and stock, which can help to identify overbought or oversold conditions.

3. **Bollinger Bands**: The program calculates the Bollinger Bands for both the cryptocurrency and stock, providing a measure of price volatility.

### Risk Analysis

The program conducts a risk analysis of the selected cryptocurrency and stock by calculating the following metrics:

1. **Standard Deviation**: The program calculates the annualized standard deviation for the cryptocurrency and stock, providing a measure of their price volatility.

2. **Value at Risk (VaR)**: The program calculates the 95% VaR for both the cryptocurrency and stock, estimating the potential loss that could occur with a 95% confidence level.

## Conclusion

Cryptostock Analytica provides a comprehensive analysis of the relationship between selected cryptocurrencies and stocks. The visualizations and calculations enable users to better understand the price trends, market conditions, and potential risks associated with their chosen assets.
