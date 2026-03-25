![Python](https://img.shields.io/badge/Python-3.x-blue)
![Status](https://img.shields.io/badge/Project-Completed-green)
# 📊 Stock Market Trend & Volatility Analysis with Prediction

## 📌 Overview

This project focuses on analyzing stock market data to understand **price trends, volatility, and relationships between multiple stocks**, and to build a **machine learning model for price prediction**.

The analysis is performed on major stocks including **RELIANCE, TCS, and NIFTY 50 index**, providing insights into both individual stock behavior and overall market performance.

---

## 🎯 Objectives

* Analyze stock price trends over time
* Measure volatility and risk using statistical methods
* Study correlation between multiple stocks
* Build a predictive model for future stock prices
* Apply technical indicators like RSI for decision-making

---

## 📂 Dataset

* Source: Yahoo Finance

* Stocks Used:

  * RELIANCE
  * TCS
  * NIFTY 50 (^NSEI)

* Features:

  * Open, High, Low, Close, Volume

---

## ⚙️ Technologies & Tools Used

* **Python**
* **Pandas, NumPy** → Data manipulation
* **Matplotlib, Seaborn** → Data visualization
* **Scikit-learn** → Machine learning
* **Jupyter Notebook** → Development environment

---

## 🔍 Project Workflow

### 🧹 Data Cleaning

* Removed unnecessary rows and structured dataset
* Checked for missing values and duplicates
* Converted date column to datetime format

---

### ⚙️ Feature Engineering

* Extracted closing prices
* Calculated daily returns
* Computed rolling volatility

---

### 📈 Trend Analysis

* Normalized stock prices (Base = 100)
* Compared performance of multiple stocks

---

### 📉 Volatility Analysis

* Calculated standard deviation of returns
* Analyzed rolling volatility (20-day window)

---

### 📈 RSI Indicator

* Implemented Relative Strength Index (RSI)
* Identified overbought (>70) and oversold (<30) conditions

---

### 🔗 Correlation Analysis

* Generated correlation heatmap
* Studied relationships between stocks

---

### 🤖 Prediction Model

* Built Linear Regression model
* Predicted next-day stock prices
* Evaluated using Mean Squared Error (MSE)

---

## 📊 Key Insights

* TCS showed stronger growth compared to RELIANCE
* NIFTY index exhibited lower volatility than individual stocks
* Strong positive correlation observed between stocks and market index
* RSI helped identify potential buy/sell signals

---

## 🚀 Future Enhancements

* Implement LSTM deep learning model
* Add real-time stock data integration
* Build interactive dashboard using Streamlit
* Deploy project as a web application

---
## 👨‍💻 Project Developer
Ankit Pandey  
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

This project demonstrates a complete **end-to-end data analytics workflow**, including data preprocessing, visualization, statistical analysis, and machine learning, applied to real-world financial data.
