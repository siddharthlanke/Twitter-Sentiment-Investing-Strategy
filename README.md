# Twitter(X)-Sentiment-Investing-Strategy

## Overview
This project explores a sentiment-based investing strategy using Twitter engagement data. It involves analyzing Twitter data to gauge sentiment, constructing portfolios based on engagement ratios, and assessing their performance against market benchmarks.

## Usage

### Sentiment Analysis
1. Load the sentiment data into your Python environment.
2. Calculate the engagement ratio by dividing the number of comments by the number of likes.
3. Filter the data to include only stocks with sufficient engagement, typically those with a minimum threshold of likes and comments.

### Portfolio Construction
1. Aggregate the sentiment data on a monthly basis.
2. Rank stocks based on their engagement ratio within each month.
3. Select the top-ranked stocks for each month to form the portfolio.

### Market Data Retrieval
1. Download market data for the selected stocks using a financial data provider such as Yahoo Finance.
2. Optionally, download market data for a market benchmark, such as NASDAQ, for comparison purposes.

### Performance Evaluation
1. Calculate the returns of the constructed portfolio over time.
2. Compare the portfolio returns with the returns of the market benchmark to evaluate the performance of the sentiment-based investing strategy.

