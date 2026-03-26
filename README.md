![Python](https://img.shields.io/badge/Python-3.x-blue)
![Status](https://img.shields.io/badge/Project-Completed-green)
# 📊 Stock Market Trend, Volatility & Prediction Analysis

## 📌 Overview

This project performs an in-depth analysis of stock market data to understand **price trends, volatility, risk behavior, and inter-stock relationships**, along with building a **machine learning model for stock price prediction**.

The analysis is conducted on major Indian stocks including **RELIANCE, TCS, and NIFTY 50 index**, providing both micro (stock-level) and macro (market-level) insights.

---

## 🎯 Objectives

* Analyze stock price trends over time
* Measure volatility and financial risk
* Understand relationships between multiple stocks
* Evaluate return distributions and cumulative growth
* Build a predictive model for next-day stock prices
* Apply technical indicators like RSI for decision-making

---

## 📂 Dataset

* **Source:** Yahoo Finance
* **Stocks Used:** RELIANCE, TCS, NIFTY 50 (^NSEI)
* **Features:** Open, High, Low, Close, Volume

---

## ⚙️ Technologies & Tools Used

* **Python**
* **Pandas, NumPy** → Data processing
* **Matplotlib, Seaborn** → Visualization
* **Scikit-learn** → Machine Learning
* **Jupyter Notebook** → Development

---

## 🔍 Project Workflow

### 🧹 Data Cleaning

* Removed unnecessary rows and formatted dataset
* Converted date to datetime format
* Checked for missing values and duplicates

---

### ⚙️ Feature Engineering

* Extracted closing prices
* Calculated daily returns
* Computed rolling volatility

---

### 📈 Trend Analysis

* Normalized stock prices (Base = 100)
* Compared performance across multiple stocks

---

### 📉 Returns & Volatility Analysis

* Calculated daily returns
* Measured risk using standard deviation
* Analyzed rolling volatility trends

---

### 📦 Returns Distribution ⭐

* Visualized distribution of daily returns
* Identified spread, skewness, and extreme values
* Helped understand risk behavior

---

### 📊 Cumulative Returns ⭐

* Calculated total growth of stocks over time
* Compared long-term investment performance

---

### 📈 RSI Indicator

* Implemented Relative Strength Index (RSI)
* Identified overbought (>70) and oversold (<30) conditions

---

### 🔗 Correlation Analysis

* Generated correlation heatmap
* Analyzed relationships between stocks

---

### 📊 Scatter Plot Analysis ⭐

* Visualized relationship between stock returns
* Identified correlation patterns and diversification opportunities

---

### 🤖 Prediction Model

* Built Linear Regression model
* Predicted next-day stock prices
* Evaluated using Mean Squared Error (MSE)

---

## 📊 Key Insights

* TCS demonstrated stronger growth compared to RELIANCE
* NIFTY index exhibited lower volatility than individual stocks
* Daily return distribution revealed varying risk levels
* Strong positive correlation observed between stocks and market index
* RSI helped identify potential buy/sell opportunities
* Scatter plots confirmed relationships between stock returns

---

## 🚀 Future Enhancements

* Implement LSTM deep learning model
* Integrate real-time stock data
* Build interactive dashboard using Streamlit
* Deploy as a web application

---

## 👨‍💻 Project Developer

**Ankit Pandey**
🔗 LinkedIn: https://www.linkedin.com/in/ankit2608/
---

## ⭐ How to Run

1. Clone the repository
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook

---

## 📌 Conclusion

This project demonstrates a complete **end-to-end financial data analytics pipeline**, combining statistical analysis, visualization, and machine learning to extract meaningful insights from stock market data.
