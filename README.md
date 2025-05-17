# ADS_8138_CSBS_TEAM_9
## Problem: 
Predicting the future price of a stock or financial asset accurately is a complex and challenging task due to various factors, including market dynamics, economic indicators, and investor sentiment.

## Objective: 
Develop a stock price prediction system that leverages historical data, market trends, and machine learning to provide accurate short-term and long-term stock price forecasts for a given company’s stock.

Common dependencies may include Python programming language(platforms such as  Python IDLE,google colab,etc.) and libraries such as scikit-learn and data sources.

## Steps
1) Install the required dependencies such as numpy, pandas and matplotlib.pyplot using package managers like pip for Python.
2) Gather dataset of any company's stock prices
3) Load historical stock price data into program
4) Select the 'Close' price column as the target variable
5) Create a new column for the next day's closing price
6) Drop the last row since there is no 'Next Close' for it
7) Split the data into features (X) and the target variable (y)
8) Split the data into training and testing sets
9) Create and train a linear regression model
10) Make predictions on the test set
11) Calculate the Mean Squared Error to evaluate the model
12) Visualize the predictions
13) Predict the stock price for a specific value
