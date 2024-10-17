S&P 500 Stocks Analysis and Portfolio Optimization
This project analyzes the S&P 500 stocks, calculates various technical indicators, and forms optimized investment portfolios using clustering and Efficient Frontier methods.

Features:

Data Collection: Downloaded historical price data for S&P 500 stocks using yfinance.
Technical Indicators: Calculated indicators like RSI, SMA, EMA, Bollinger Bands using pandas_ta.
Monthly Aggregation: Resampled data on a monthly level and selected the top 150 most liquid stocks.
Factor Analysis: Downloaded Fama-French Factors and calculated rolling betas.
K-Means Clustering: Grouped stocks based on calculated features.
Portfolio Optimization: Built portfolios using Efficient Frontier with max Sharpe ratio.
Performance Visualization: Compared optimized portfolio returns with the S&P 500 benchmark.

Prerequisites
Python 3.x
yfinance
pandas, numpy
pandas_ta
scikit-learn
cvxpy, pyportfolioopt


How to Use
Clone the repository:
bash
Copy code
git clone https://github.com/your_username/sp500-analysis.git


Install required libraries:
bash
Copy code
pip install -r requirements.txt
Run the main analysis script:
bash
Copy code
python main.py



Results
Visualization of the portfolio returns vs. S&P 500.
Insights on stock clusters and sector performance.
Future Improvements
Incorporate more factors into the model.
Explore alternative clustering methods.
Add more visualization techniques for deeper analysis.
