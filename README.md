# Bitcoin Market Sentiment vs Trader Performance Analysis

## Objective
The goal of this analysis is to study the relationship between Bitcoin market sentiment
(Fear & Greed Index) and trader performance from Hyperliquid historical trading data.

## Datasets Used
1. Bitcoin Market Sentiment Dataset
   - Columns include: Date, Classification
2. Hyperliquid Historical Trader Data
   - Columns include: account, symbol, execution price, size, side, time, closedPnL, leverage, etc.

## Approach
- Download and load both datasets
- Clean and standardize the data
- Merge trader data with daily market sentiment using trade date
- Analyze trader profitability across sentiment categories
- Perform deeper breakdowns by side, symbol, account, leverage, and time
- Use statistical testing and outlier-aware metrics to validate insights

## Key Outcome
This project identifies how trader performance changes under Fear, Greed, and Extreme Greed market conditions,
and shows how sentiment can be used as an input for smarter trading strategy design.
