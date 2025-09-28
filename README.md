# Time Series Trading Backtest

A hands-on quantitative finance project using Pandas to analyze Apple stock time series data, compute multi-asset returns, and backtest a long-only trading strategy—no for-loops, pure vectorized operations. Includes candlestick charts, resampling, rolling windows, and performance evaluation. Perfect for learning time series analysis in finance.


## Installation

Clone the repository:
```bash

git clone https://github.com/stkisengese/time-series-trading-backtest.git
cd time-series-trading-backtest
```

Install the dependencies:
```bash

pip install -r requirements.txt
```

## Usage

Start Jupyter Notebook:
```bash

jupyter notebook
```

Open one of the notebooks:

    financial_data.ipynb

    multi_asset_returns.ipynb

    backtest.ipynb

    integer_series.ipynb

### Data

The AAPL.csv file contains historical stock data for Apple Inc. (AAPL) from 1980-12-12 to 2021-01-29. The data was downloaded from Yahoo Finance.
Notebooks
**financial_data.ipynb**

This notebook demonstrates how to:

    Load and preprocess financial time series data.

    Create candlestick charts using Plotly.

    Resample time series data to different frequencies.

    Calculate and visualize rolling windows (moving averages).

**multi_asset_returns.ipynb**

This notebook demonstrates how to:

    Simulate market data for multiple assets.

    Create a MultiIndex DataFrame.

    Pivot the data to have tickers as columns.

    Calculate daily returns for multiple assets without using a for-loop.

**backtest.ipynb**

This notebook demonstrates how to:

    Backtest a simple long-only trading strategy.

    Compare a random trading signal to an "always buy" strategy.

    Calculate and visualize the cumulative PnL of the strategies.

**integer_series.ipynb**

This notebook demonstrates how to:

    Create a time series of integers.

    Calculate a 7-day moving average.

## License

This project is licensed under the [MIT License](LICENSE)