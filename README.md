Project Description: Coca-Cola Stock Price Analysis and Prediction
This project focuses on analyzing and predicting the stock prices of Coca-Cola (Ticker: KO) using historical stock data and machine learning techniques. It aims to explore the stock’s past behavior, extract patterns through visualizations, and forecast future trends using regression models.

🎯 Objectives
To analyze Coca-Cola’s historical stock price data using Python libraries.

To visualize important trends and patterns such as daily closing prices, moving averages, and volatility.

To build a prediction model using MinMaxScaler and regression to estimate future price movements.

To evaluate model performance using error metrics like Mean Squared Error (MSE).

🧪 Methodology
1. Data Collection
Data is fetched from Yahoo Finance or loaded from a local CSV file containing Coca-Cola stock data with columns like Date, Open, High, Low, Close, and Volume.

2. Data Preprocessing
Handled missing values and formatted timestamps.

Normalized features using MinMaxScaler to scale data between 0 and 1.

Created lag variables to train the model on past price movement.

3. Exploratory Data Analysis (EDA)
Used Matplotlib and Seaborn to create plots of:

Daily closing prices

Volume traded

50-day and 200-day moving averages

Stock volatility over time

4. Modeling
Applied linear regression and other models to predict stock prices.

Evaluated predictions using:

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

🔍 Key Findings
Coca-Cola stock prices show seasonal trends and follow a relatively stable pattern over the years.

Volume spikes usually indicate important market events or investor sentiment shifts.

The 200-day moving average provided a better long-term view and helped spot bullish or bearish momentum.

The prediction model captured the overall trend, though it slightly lagged during sudden spikes or drops — common in time-series predictions.

RMSE was low, suggesting that the model’s predictions are close to actual values.

📌 Conclusion
This project provides a basic yet practical approach to financial data modeling and stock trend forecasting. With further enhancement (e.g., using LSTM or ARIMA), prediction accuracy can improve significantly. The project demonstrates the potential of machine learning in financial markets using Python.
# 📊 Stock Market Strategy Optimization with Technical Indicators

Hey there! 👋  
This project is all about exploring and optimizing trading strategies using Python, with a focus on technical indicators and backtesting. I’ve pulled in historical OHLCV stock data, applied dozens of indicators using `finta`, and built a customizable strategy that we tested and tuned using the `backtesting` library.

---

## 🔍 What This Project Does

- Loads and cleans stock market data (OHLCV format)
- Applies a huge list of technical indicators (moving averages, momentum, volatility bands, etc.)
- Visualizes selected indicators and their behavior on price movements
- Builds a crossover trading strategy (`Sma4Cross`) and tests its performance
- Optimizes the strategy using parameter tuning to find the best combo
- Analyzes performance metrics like return, drawdown, win rate, and more
- Generates a heatmap to show how different parameter values affect results

---

## 🧪 Tools & Libraries Used

- **Python 3.x**
- **pandas** – for data manipulation
- **matplotlib** – for charting
- **finta** – for dozens of technical indicators
- **backtesting.py** – to simulate and optimize trading strategies
- **numpy**

---

## 🎯 Why I Did This

I wanted to explore how technical indicators behave across different market conditions and how we can use them to build rule-based strategies. The project also helped me understand the challenges of overfitting and realistic backtesting.

---

## 🚀 How to Run It

1. Clone the repo or download the files
2. Make sure you have Python installed
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
