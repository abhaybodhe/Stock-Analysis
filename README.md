# Dow Jones Industrial Average (DJAI) Stock Analysis

This project performs a comprehensive analysis of the Dow Jones Industrial Average (DJAI) stocks, implements a mean reversion trading strategy, and compares its performance to the DJAI benchmark.

## Features

- Fetches up-to-date DJAI constituent data from Wikipedia
- Downloads 10 years of historical stock data for DJAI components using yfinance
- Implements a mean reversion strategy based on daily biggest losers
- Calculates key performance metrics: annualized return, volatility, Sharpe ratio, and max drawdown
- Compares the strategy's performance against the DJAI benchmark (DIA ETF)

## Requirements

- Python 3.7+
- pandas
- yfinance
- numpy
- matplotlib (for visualization, if needed)

## Usage

Run the Jupyter notebook `DJAI Stock Analysis.ipynb` to execute the analysis:

```
jupyter notebook "DJAI Stock Analysis.ipynb"
```

The notebook will guide you through the following steps:

1. Fetching DJAI constituent data
2. Downloading historical stock data
3. Calculating daily returns
4. Implementing the mean reversion strategy
5. Calculating performance metrics
6. Comparing results with the DJAI benchmark

## Results

The notebook will output performance metrics for both the mean reversion strategy and the DJAI benchmark, including:

- Annualized Return
- Annualized Volatility
- Sharpe Ratio

It will also provide a comparison of the strategy's performance against the benchmark.

## Contributing

Contributions to improve the analysis or add new features are welcome. Please feel free to submit a pull request or open an issue to discuss potential changes/additions.

## License

This project is open source and available under the [MIT License](LICENSE).

## Disclaimer

This project is for educational purposes only. It is not financial advice and should not be used to make investment decisions. Always do your own research and consult with a qualified financial advisor before making any investment.
