# portfolio-risk-analysis-python
Python project for portfolio risk analysis and optimization using historical data for Amazon, Apple and Meta. Implements Global Minimum Variance and minimum-VaR portfolios, parametric and historical VaR, Expected Shortfall, time scaling and financial data visualization.

# Project overview
This project analyses the risk of a portfolio composed of Apple, Amazon and Meta shares using Python and historical daily price data.
The analysis compares different portfolio construction and risk measurement approaches, including the Global Minimum Variance Portfolio and the minimum-Value-at-Risk portfolio.

# Objectives 
The main objectives of the project are:
- Calculate daily stock returns and losses
- Analyse volatility and correlations
- Construct the Global Minimum Variance Portfolio
- Estimate parametric and historical Value at Risk
- Calculate Expected Shortfall
- Estimate risk over daily, weekly and annual horizons
- Compare minimum-variance and minimum-VaR portfolios
- Evaluate the impact of short-selling constraints

# Methodology
The Global Minimum Variance Portfolio is obtained by minimizing portfolio variance subject to the condition that the portfolio weights sum to one. The analysis assumes an initial portfolio value of $10,000 and a 99% confidence level.

# Main results
The results show that the minimum-variance and minimum-VaR portfolios have similar but not identical allocations because Value at Risk depends on both expected losses and portfolio volatility. The comparison between parametric and historical risk measures also highlights the limitations of the normality assumption when modelling equity returns.

# Technologies
Python, pandas, NumPy, SciPy, Matplotlib, Seaborn, Jupyter Notebook

# Data availability
The original dataset was provided for academic use and is not included in this public repository. The analysis requires historical daily prices for Apple, Amazon and Meta.
