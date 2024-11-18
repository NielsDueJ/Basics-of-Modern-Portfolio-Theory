README: Basic Portfolio Theory Notebook

### Overview
Concepts of portfolio theory introduced through data preparation, analysis, and optimization. It demonstrates the Markowitz Mean-Variance Model, efficient frontier construction, Sharpe ratio maximization, and backtesting, providing a hands-on guide to understanding risk-return trade-offs in portfolio management.

### Key Highlights

- **Setup**: Import essential libraries for data analysis, visualization, optimization, and factorability checks using `pandas`, `numpy`, `matplotlib`, `scipy`, and `factor-analyzer`.
- **Data Preparation**: Load and clean stock return data, convert daily to weekly returns, and integrate risk-free rate data (T-Bills). Handle missing data by dropping incomplete rows or columns.
- **Analysis**: Evaluate annualized returns, volatility, Sharpe ratio, and maximum drawdown. Use regression (CAPM) to calculate Alpha and Beta for individual stocks.
- **Covariance Matrix**: Analyze stock relationships by computing and scaling the covariance matrix. Check factorability using Bartlett’s and KMO tests for potential factor analysis.
- **Markowitz Model**: Optimize portfolio allocation by minimizing variance under constraints, including budget and target returns. Solve using `scipy.optimize.minimize` and visualize results.
- **Efficient Frontier**: Generate portfolios across target returns to map the trade-off between risk and return. Visualize how portfolio concentration shifts with increasing returns.
- **Sharpe Ratio Maximization**: Identify the portfolio with the highest Sharpe ratio, demonstrating risk-adjusted performance optimization.
- **Risk-Free Rate Integration**: Incorporate risk-free rate as an asset to calculate a new efficient frontier, highlighting the impact of leveraging or diversifying with T-Bills.
- **Backtesting**: Validate portfolio allocations using historical returns, showcasing real-world performance through Buy-and-Hold strategies and Ex-Post Mean-Variance plots.

### How to Use
Run the notebook sequentially for a structured learning experience or modify key parameters like target returns and timeframes to explore custom scenarios. Use visualizations to analyze diversification, portfolio risks, and return dynamics.

### Requirements
- **Python Version**: 3.x
- **Libraries**: Install with `pip install pandas numpy matplotlib scipy factor-analyzer scikit-learn`.

### Conclusion
This notebook is a practical tool for exploring portfolio theory, emphasizing the benefits of diversification and risk-return optimization. Experiment with the provided datasets to deepen your understanding and apply these concepts in real-world scenarios.
