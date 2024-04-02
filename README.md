# Stock-Portfolio-Analyzer
Python program 

```markdown
# Stock Portfolio Analysis

This Python program allows you to analyze the performance of a stock portfolio over time. It fetches historical stock prices using the Yahoo Finance API, calculates the daily returns of the portfolio, and plots the cumulative returns over time using matplotlib.

## Features

- Define a stock portfolio with different stocks, quantities, and purchase prices
- Calculate the current value of the portfolio
- Plot the cumulative returns of the portfolio over a specified period (e.g., 1 year)

## Installation

1. Clone the repository or download the source code.
2. Install the required dependencies:

```
pip install yfinance matplotlib
```

## Usage

1. Import the `StockPortfolio` class from the source file.
2. Create an instance of the `StockPortfolio` class.
3. Add stocks to the portfolio using the `add_stock` method, specifying the stock symbol, quantity, and purchase price.
4. Calculate the current value of the portfolio using the `get_portfolio_value` method.
5. Plot the cumulative returns of the portfolio over time using the `plot_cumulative_returns` method.

```python
from stock_portfolio import StockPortfolio

# Create a new portfolio
portfolio = StockPortfolio()

# Add stocks to the portfolio
portfolio.add_stock('AAPL', 10, 150)  # 10 shares of Apple bought at $150 each
portfolio.add_stock('MSFT', 5, 200)   # 5 shares of Microsoft bought at $200 each

# Get the current value of the portfolio
current_value = portfolio.get_portfolio_value()
print(f"Current portfolio value: ${current_value:.2f}")

# Plot the cumulative returns of the portfolio over the last year
portfolio.plot_cumulative_returns()
```

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
```


