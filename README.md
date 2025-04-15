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
