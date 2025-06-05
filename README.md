
# 📈 Bitcoin Price Prediction Using LSTM

This project uses a Long Short-Term Memory (LSTM) neural network to predict Bitcoin (BTC) closing prices based on historical data.

## 🔍 Overview

LSTM networks are well-suited for time series forecasting due to their ability to learn long-term dependencies. This project demonstrates how to preprocess BTC-USD price data, train an LSTM model, and visualize predictions.

---

## 📦 Requirements

- Python 3.7+
- pandas
- numpy
- matplotlib
- scikit-learn
- yfinance
- TensorFlow or Keras

Install dependencies:

```bash
pip install numpy pandas matplotlib scikit-learn yfinance tensorflow
import yfinance as yf
data = yf.download('BTC-USD', start='2018-01-01', end='2025-01-01')
LSTM(50) → Dropout → LSTM(50) → Dropout → Dense(1)
