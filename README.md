# Simple Moving Average Crossover Trading Algorithm

## Project Description

This project implements a basic algorithmic trading strategy using Python. 

The algorithm uses a Moving Average Crossover strategy, one of the fundamental techniques in technical analysis and algorithmic trading. This project serves as a starting point to understand the basics of strategy development, backtesting, and performance analysis in algorithmic trading.

## Algorithm Description

### Strategy: Moving Average Crossover

The core of this algorithm is a Moving Average Crossover strategy using two Simple Moving Averages (SMA):

1. Short-term SMA: 25-day Simple Moving Average
2. Long-term SMA: 50-day Simple Moving Average

#### Trading Signals:

- **Buy Signal**: Generated when the 25-day SMA crosses above the 50-day SMA
- **Sell Signal**: Generated when the 25-day SMA crosses below the 50-day SMA

This strategy aims to capture trends in the market while filtering out some of the short-term price noise.

### Implementation Details:

1. **Data Acquisition**: Historical price data is fetched using the yfinance library.
2. **Indicator Calculation**: 25-day and 50-day SMAs are calculated using pandas.
3. **Signal Generation**: Buy/sell signals are generated based on SMA crossovers.
4. **Backtesting**: The strategy is backtested on historical data to evaluate its performance.
5. **Performance Analysis**: Uses the QuantStats library to generate comprehensive performance metrics and visualizations.

## Key Features

- Fetches real market data using yfinance
- Implements a simple yet widely-used trading strategy
- Backtests the strategy on historical data
- Generates performance metrics including Sharpe Ratio, Max Drawdown, and Calmar Ratio
- Creates visualizations like Monthly Returns Heatmap and Drawdown Periods

## Disclaimer

This project is for educational purposes only. It is not financial advice and should not be used for actual trading without proper risk management and further development. Real-world trading involves significant risk and requires in-depth knowledge, which is beyond the scope of this educational project.

## Future Enhancements

- Implement more sophisticated strategies
- Add risk management techniques
- Incorporate fundamental analysis
- Explore machine learning approaches to strategy development

We welcome contributions and suggestions to improve this educational tool!
