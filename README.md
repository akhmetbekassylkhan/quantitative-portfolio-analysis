# Portfolio Risk Analysis and Optimization Using Python

## About the Project

This is my first independent quantitative finance project. I created it to explore how Python, mathematics, and financial data can be used to understand investment risk and portfolio performance.

The main focus of this project is portfolio diversification and optimization. I wanted to investigate whether combining different asset classes could produce a better balance between risk and return than investing in a single market index.

## Research Question

How does portfolio diversification across equities, technology stocks, gold, and bonds affect risk-adjusted returns under different market conditions?

## Assets

I selected four ETFs representing different types of investments:

| Ticker | Asset | Description |
|---|---|---|
| SPY | Equities | Tracks the S&P 500 |
| QQQ | Technology stocks | Tracks the Nasdaq-100 |
| GLD | Gold | Provides exposure to gold prices |
| TLT | Government bonds | Tracks long-term U.S. Treasury bonds |

## Data and Tools

- Data source: Yahoo Finance
- Period: January 2015 – December 2025
- Language: Python
- Libraries: pandas, NumPy, Matplotlib, Seaborn, yfinance

## Methodology

The project includes the following steps:

1. Collecting historical market data.
2. Calculating daily and cumulative returns.
3. Measuring annual return and volatility.
4. Studying correlations between assets.
5. Constructing portfolios with different asset weights.
6. Calculating Sharpe ratios.
7. Comparing portfolio performance across different market periods.
8. Running a Monte Carlo simulation with 10,000 random portfolios.
9. Testing the selected portfolio on unseen historical data.
10. Comparing its performance with the SPY benchmark.
    
## Visualizations

### Growth of $1

![Growth of $1](images/growth_of_1_dollar.png)

### Correlation Matrix

![Correlation Matrix](images/correlation_matrix.png)

### Monte Carlo Simulation

![Monte Carlo Simulation](images/monte_carlo_simulation.png)

### Optimized Portfolio vs. SPY

![Optimized Portfolio vs. SPY](images/optimized_portfolio_vs_spy.png)

## Out-of-Sample Results

The portfolio was optimized using data from 2015–2022 and evaluated on a separate testing period from 2023–2025.

| Metric | Optimized Portfolio | SPY |
|---|---:|---:|
| Annual Return | 28.76% | 21.88% |
| Annual Volatility | 12.90% | 15.34% |
| Sharpe Ratio | 2.229 | 1.426 |

During this testing period, the optimized portfolio achieved a higher annualized return and Sharpe ratio, while experiencing lower annualized volatility than SPY.

## What I Learned

Before starting this project, I had very limited experience with Python and programming.

While working on it, I learned how to:

- Work with financial datasets using pandas.
- Calculate investment returns and portfolio volatility.
- Understand correlation and diversification.
- Apply the Sharpe ratio to compare investment performance.
- Use Monte Carlo simulation to explore portfolio allocations.
- Separate training and testing data to evaluate a strategy more carefully.

This project also helped me understand how quantitative methods can be applied to real financial questions.

## Limitations

- Historical performance does not guarantee future results.
- Transaction costs, taxes, and management fees are not included.
- A simplified risk-free rate of 0% is used for Sharpe ratio calculations.
- Monte Carlo simulation tests randomly generated long-only portfolio weights and does not guarantee a global optimum.
- The out-of-sample test covers only one historical period.

## Conclusion

This project suggests that diversification and quantitative portfolio optimization can improve risk-adjusted performance under certain market conditions.

However, the results should be interpreted carefully and should not be considered investment advice.

## Author

Akhmetbek Assylkhan
