# 📈 Stock Price Forecasting Using Machine Learning

## 📌 Overview
This project focuses on forecasting stock prices using historical data stored in a CSV file.  
The goal is to analyze stock trends and predict future prices using a machine learning regression model.

The project is implemented entirely in **Python using Google Colab** and follows a complete **end-to-end data science workflow**.

---

## 🎯 Objectives
- Load and preprocess historical stock price data
- Perform time-series visualization
- Apply feature engineering for forecasting
- Train a machine learning model
- Predict future stock prices
- Visualize actual vs predicted values

---

## 📊 Dataset
- **Format:** CSV file
- **Columns Used:**
  - Date
  - Open
  - High
  - Low
  - Close
  - Volume
- **Target Variable:** Close price (future values)

---

## 🛠️ Tech Stack
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 🔍 Project Workflow
1. Upload and load CSV dataset
2. Data cleaning and preprocessing
3. Date-time indexing
4. Exploratory data analysis (EDA)
5. Feature engineering (future price shift)
6. Train-test split
7. Model training using Linear Regression
8. Model evaluation using Mean Squared Error (MSE)
9. Forecasting future stock prices
10. Visualization of results

---

## 🤖 Machine Learning Model
- **Algorithm:** Linear Regression
- **Reason:** Simple baseline model for time-series forecasting
- **Evaluation Metric:** Mean Squared Error (MSE)

---

## 📈 Results
- Successfully forecasted stock prices for the next 30 days
- Visual comparison between historical prices and predicted prices
- Model performance evaluated quantitatively

---

## ⚠️ Limitations
- Linear Regression cannot capture complex market patterns
- External factors like news and market sentiment are not considered
- Predictions are for educational purposes only

---

## 🚀 Future Improvements
- Implement LSTM (Deep Learning)
- Add technical indicators (RSI, MACD, Moving Averages)
- Use ARIMA / SARIMA models
- Build an interactive Streamlit dashboard
- Extend to multi-stock forecasting

---

## 📁 Repository Structure
