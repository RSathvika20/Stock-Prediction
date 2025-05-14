# 📈 Stock Price Prediction using LSTM

A deep learning-based time-series forecasting model built using Long Short-Term Memory (LSTM) networks to predict future stock prices based on historical market data.

---

## 🚀 Overview

Stock markets are inherently volatile and influenced by numerous factors. This project aims to leverage the power of LSTM neural networks to model historical stock data and forecast future closing prices. The project focuses on preprocessing financial time series data, training an LSTM model, and visualizing the results to evaluate performance.

---

## 🧠 Key Features

- Predicts future **closing stock prices** based on historical trends
- Implements **LSTM neural networks** for capturing time dependencies
- Visualizes predictions vs. actual prices for performance evaluation
- Supports **customizable input sequences** (e.g., 60-day window)
- Modular design for **easy experimentation and extension**

---

## 🛠️ Tech Stack

| Tool          | Purpose                            |
|---------------|-------------------------------------|
| Python        | Core programming language           |
| Pandas, NumPy | Data handling and manipulation      |
| Matplotlib    | Data visualization                  |
| Scikit-learn  | Data preprocessing and scaling      |
| TensorFlow/Keras | LSTM model creation and training |

---

## 📊 Dataset

- **Source**: [Yahoo Finance](https://finance.yahoo.com/)
- **Features Used**: `Open`, `High`, `Low`, `Close`, `Volume`, `Date`
- **Target**: Closing price (`Close`)

> You can change the ticker symbol and date range in the script to work with any publicly traded company.

---

## 📁 Project Structure

