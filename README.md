# quantitativeportfolio

# 📊 Smart Portfolio Optimizer

Welcome to the portfolio optimizer that thinks it's smarter than your financial advisor! Because why settle for boring index funds when you can pretend you're Warren Buffett?

## ✨ Features

- **Multi-Asset Analysis**: Combines stocks (AAPL, MSFT, etc.), crypto (BTC), and commodities (GLD)
- **Smart Optimization**: Uses Modern Portfolio Theory to find the best asset allocation
- **Risk Analysis**: Calculates key risk metrics and visualizes them
- **Interactive Visualizations**: See your portfolio performance with clean, informative charts
- **Historical Testing**: Tests strategy against real market data from 2015-2024

## 🚀 Quick Start

1. Install required packages:
```python
pip install yfinance pandas pypfopt matplotlib seaborn
```

2. Run the analysis:
```python
python Quantitative_Portfolio_Management.ipynb
```

## 📈 What It Does

The tool performs these key steps:

1. **Data Collection**
   - Fetches historical data for 10 assets including tech stocks, crypto, and gold
   - Handles missing data and adjusts for splits/dividends

2. **Returns Analysis**
   - Calculates daily returns
   - Creates visual distributions
   - Computes key statistics

3. **Portfolio Optimization**
   - Finds the optimal asset weights
   - Maximizes Sharpe ratio
   - Shows you exactly where to invest

4. **Performance Visualization**
   - Clean, easy-to-read charts
   - Portfolio allocation pie chart
   - Cumulative returns over time

## 👩‍💻 Usage Example

```python
# Load your assets
tickers = ['AAPL', 'MSFT', 'META', 'INTC', 'DIS', 'AMZN', 'KO', 'TSLA', 'BTC-USD', 'GLD']

# Run optimization
weights = optimize_portfolio(tickers)

# View results
plot_portfolio_performance(weights)
```

## ⚠️ Friendly Reminder

Remember: Past performance doesn't guarantee future results. This tool is for educational purposes - always do your own research!

## 🤝 Contributing

Found a way to make it better? PRs welcome! Just keep it simple and well-documented.

## 📝 License

MIT License - Feel free to use it, modify it, share it.

---

Built with Python and a dash of financial wisdom. Questions? Open an issue!
