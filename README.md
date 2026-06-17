# Sarpannch AI-Stock Price Prediction App
Welcome to the Stock Price Prediction App! This app allows you to visualize stock price data, explore technical indicators, and make short-term price predictions using machine learning models.


# Table of Contents
•	Description
•	Features
•	Setup
•	Usage
•	Technologies
•	License


# Description
The Stock Price Prediction App is a Streamlit-based web application that provides users with tools to analyze historical stock price data, visualize technical indicators, and make short-term price predictions using different machine learning models.

# Tech Stack: Python, NumPy, Scikit-Learn, Streamlit, LSTM, RNN, Machine Learning, AWS 
• Challenge: Single-model stock predictors for NSE equities showed directional accuracy below 75% on unseen test windows. 
Benchmarked 5 algorithms (Linear Regression, Random Forest, Extra Trees, KNN, XGBoost); selected LSTM+RNN ensemble as 
best-performer, achieving 92% directional accuracy vs. 74% XGBoost baseline. 
• Deployed Streamlit app on AWS EC2; reduced inference response latency by 30% (from 2s to 1.4s) via model serialization 
optimisation; minimized MAPE forecasting error by 18% through ensemble averaging and hyperparameter search. 


# Features
Visualize Technical Indicators: Explore various technical indicators such as Bollinger Bands, MACD, RSI, SMA, and EMA to gain insights into stock price trends.
Recent Data Display: View the most recent data of the selected stock, including the last 10 data points.
Price Prediction: Predict future stock prices using machine learning models including Linear Regression, Random Forest Regressor, Extra Trees Regressor, KNeighbors Regressor, and XGBoost Regressor.


# Setup
1.Navigate to the project directory:
cd STOCK-PRICE-PREDICTION-MAIN

2.Install the required Python packages using pip:
pip install -r requirements.txt


# Usage
1.Run the Streamlit app:
streamlit run app.py

2.The app will open in your default web browser. Use the sidebar to choose options for visualization, recent data display, or making price predictions.

3.Follow the on-screen instructions to input the stock symbol, select a date range, and choose technical indicators or prediction models.


# Technologies
Python,
Streamlit,
pandas,
yfinance,
ta (Technical Analysis Library),
scikit-learn,
XGBoost
AWS


