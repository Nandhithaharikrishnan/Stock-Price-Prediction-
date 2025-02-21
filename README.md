# Stock Price Prediction App
Welcome to the Stock Price Prediction App! This app allows you to visualize stock price data, explore technical indicators, and make short-term price predictions using machine learning models.

Table of Contents
•	Description
•	Features
•	Setup
•	Usage
•	Technologies
•	License

Description
The Stock Price Prediction App is a Streamlit-based web application that provides users with tools to analyze historical stock price data, visualize technical indicators, and make short-term price predictions using different machine learning models.

Features
Visualize Technical Indicators: Explore various technical indicators such as Bollinger Bands, MACD, RSI, SMA, and EMA to gain insights into stock price trends.
Recent Data Display: View the most recent data of the selected stock, including the last 10 data points.
Price Prediction: Predict future stock prices using machine learning models including Linear Regression, Random Forest Regressor, Extra Trees Regressor, KNeighbors Regressor, and XGBoost Regressor.

Setup
1.Clone the repository:
git clone https://github.com/vikasharma005/Stock-Price-Prediction.git
2.Navigate to the project directory:
cd stock-price-prediction-app
3.Install the required Python packages using pip:
pip install -r requirements.txt


Usage
1.Run the Streamlit app:
streamlit run app.py
2.The app will open in your default web browser. Use the sidebar to choose options for visualization, recent data display, or making price predictions.
3.Follow the on-screen instructions to input the stock symbol, select a date range, and choose technical indicators or prediction models.

Technologies
Python
Streamlit
pandas
yfinance
ta (Technical Analysis Library)
scikit-learn
XGBoost


