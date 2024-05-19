Project Description: Portfolio Optimization Using Python and yFinance
Overview:
This project focuses on downloading historical stock data for a selected list of ticker symbols, processing the data to clean and filter relevant information, and optimizing a portfolio for maximal Sharpe Ratio using Python and the yFinance library.

Objectives:
Data Collection: Download historical stock data for the past 2 years using yFinance.
Data Processing: Clean and filter the data to retain only the adjusted closing prices and dates.
Portfolio Optimization: Use the PyPortfolioOpt library to calculate expected returns and the sample covariance matrix, and optimize the portfolio for maximal Sharpe Ratio.
Discrete Allocation: Allocate the portfolio based on the optimized weights and a specified total portfolio value.
Steps Involved:
Import Libraries: Import necessary libraries including yFinance for data download and pandas for data manipulation.
Download Data: Use yFinance to download historical stock data for a specified list of ticker symbols.
Save and Load Data: Save the downloaded data to a CSV file and reload it for processing.
Data Cleaning: Filter columns to retain only the 'Date' and 'Adj Close' values, drop any rows with missing dates, and ensure all columns are numeric.
Set Index: Convert the 'Date' column to datetime format and set it as the index for the DataFrame.
Calculate Expected Returns and Covariance Matrix: Use PyPortfolioOpt to calculate these metrics from the cleaned data.
Optimize Portfolio: Optimize the portfolio for maximal Sharpe Ratio and clean the resulting weights.
Sort and Print Weights: Sort the weights in descending order and print them, displaying only those with non-zero allocations.
Portfolio Performance: Print the expected portfolio performance including expected annual return, volatility, and Sharpe Ratio.
Discrete Allocation: Use the latest stock prices to perform discrete allocation of assets based on the optimized weights and a specified total portfolio value, and print the allocation results and any remaining funds.
Tools and Libraries:
Python: The primary programming language used.
yFinance: For downloading historical stock data.
pandas: For data manipulation and processing.
PyPortfolioOpt: For portfolio optimization, including calculation of expected returns, covariance matrix, and optimization for Sharpe Ratio.
Output:
The project results in a set of optimized portfolio weights for the specified ticker symbols, based on historical data, that aims to maximize the Sharpe Ratio. The portfolio performance metrics and discrete allocation of assets are also provided, helping to make informed investment decisions.

Conclusion:
This project demonstrates the use of Python for financial data analysis and portfolio optimization, leveraging powerful libraries such as yFinance and PyPortfolioOpt. It provides a comprehensive workflow from data collection to portfolio optimization and allocation, making it a valuable tool for financial analysts and investors.







