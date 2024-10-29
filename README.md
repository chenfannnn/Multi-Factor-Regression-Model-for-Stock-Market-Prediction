# Multi-Factor-Regression-Model-for-Stock-Market-Prediction
Project Overview
This project develops a multi-factor regression model to predict stock prices based on various financial, technical, and economic factors. The aim is to analyze historical stock data and multiple independent variables (factors) to predict future stock prices more accurately than a single-variable approach.

Features
Data preprocessing: Cleans and normalizes stock data, handles missing values, and prepares the dataset for regression.
Factor selection: Analyzes and selects multiple factors such as economic indicators, stock performance metrics, and technical indicators.
Multi-factor regression model: Builds a multiple linear regression model using the selected factors to predict future stock prices.
Evaluation: Tests the model performance using various evaluation metrics such as R-squared, Mean Absolute Error (MAE), and Mean Squared Error (MSE).
Visualization: Generates visual plots of actual vs predicted stock prices, regression coefficients, and factor importance.


Python 3.8+
Libraries:
pandas
numpy
scikit-learn
matplotlib
seaborn
yfinance (for fetching stock data)


Data Sources
This model uses historical stock market data from financial APIs like Yahoo Finance. You can fetch data automatically using the yfinance library or use your own datasets.

Model Details
Regression Algorithm: Ordinary Least Squares (OLS)

Independent Variables:

Technical Indicators (Moving Averages, RSI, MACD, etc.)
Financial Ratios (P/E ratio, EPS, Dividend Yield, etc.)
Economic Indicators (Interest Rates, Inflation, GDP Growth, etc.)
Dependent Variable: Stock price (typically Close price)

Evaluation Metrics
R-squared (R²): Measures the proportion of variance in the dependent variable that is predictable from the independent variables.
Mean Absolute Error (MAE): Average of the absolute errors between predicted and actual values.
Mean Squared Error (MSE): Measures the average of the squared differences between predicted and actual values.
