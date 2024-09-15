# Algorithmic Trading Strategies

## Summary

Three state-of-the-art algorithmic trading strategies are included in this repository to improve your financial analysis and decision-making capabilities. These strategies make use of Python, Pandas, Financial Data Analysis methods, sentiment analysis on Twitter, and portfolio optimization.

Among the tactics discussed are:
- Unsupervised Learning Trading Strategy: Discover the important characteristics and indicators that influence stock performance by analyzing and optimizing S&P 500 stock data.

- Twitter Sentiment Investing Strategy: NASDAQ stocks can be ranked using the Twitter Sentiment Investing Strategy, which compares sentiment to market returns.

- Intraday Trading Strategy: To identify daily and intraday market signals, use technical indicators in conjunction with the GARCH model.

## Features

- Financial Data Analysis: Compiles information on SP500 stocks and uses it to compute features and technical indicators, such as liquidity measures and moving averages.
- Portfolio Optimization: Uses stock clustering and Sharpe ratio optimization to improve decision-making.
- Twitter Sentiment Analysis: This tool pulls engagement metrics from NASDAQ stocks, ranks them, and compares their performance to the QQQ index.
- GARCH Model Intraday Strategy: This strategy uses technical indicators in conjunction with GARCH to provide accurate intraday trading signals.
- Data Visualization: Plotting and visualizing stock data and technical indicators to aid comprehension and presentation.

## Skills and Tools

- Python: Core programming language used for the project.
- Pandas: Efficient data handling and manipulation for large stock datasets.
- Financial Data Analysis: Calculating liquidity, stock performance metrics, and technical indicators.
- Portfolio Optimization: Applying Sharpe ratio optimization for stock selection.
- Data Visualization: Plotting data trends, features, and indicators for better insights.

## Prerequisites

- Python 3.x
- Pandas
- Matplotlib (for visualization)
- yfinance (for fetching stock data)
- scikit-learn (for clustering algorithms)
- statsmodels (for GARCH model implementation)

## Installation

1. Clone this repository to your local machine:
```bash
git clone https://github.com/yourusername/algorithmic-trading-strategies.git
cd algorithmic-trading-strategies
```

2. Install the required Python libraries:
```bash
pip install -r requirements.txt
```

## Usage

Unsupervised Learning Trading Strategy:
Run the script to analyze S&P 500 stock data, extract features, and calculate indicators:
```bash
python unsupervised_strategy.py
```

Twitter Sentiment Investing Strategy:
Analyze Twitter sentiment data and rank NASDAQ stocks based on engagement metrics:
```bash
python twitter_sentiment_strategy.py
```

Intraday Strategy:
Capture intraday signals using the GARCH model and technical indicators:
```bash
python intraday_strategy.py
```

## Project Details

### Unsupervised Learning Trading Strategy:

- Analyzed S&P 500 stock data using features and technical indicators like RSI and moving averages.
- Optimized data handling by aggregating stock data to a monthly level and selecting the 150 most liquid stocks, reducing processing time.
- Simplified portfolio creation using basic Sharpe ratio optimization for better decision-making and improved stock selection.

### Twitter Sentiment Investing Strategy:

- Sentiment analysis of NASDAQ stocks using Twitter engagement data.
- Compared sentiment rankings against market returns (QQQ) to evaluate investment potential.

### Intraday Trading Strategy:

- GARCH model used in combination with technical indicators to capture both daily and intraday signals for potential trades.
