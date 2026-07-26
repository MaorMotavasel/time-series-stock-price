# 📈 Time Series Stock Price Prediction using Auto-ARIMA

A time series forecasting project that models and predicts historical stock market prices using **Auto-ARIMA** (`pmdarima`).

## 📌 Project Overview
- **Goal:** Analyze historical stock prices and build an automated ARIMA model to forecast future prices.
- **Model:** Auto-ARIMA (automatically selects optimal $p, d, q$ parameters based on AIC).
- **Libraries Used:** Pandas, NumPy, Matplotlib, seaborn, pmdarima.

## 📊 Key Results
- Best ARIMA Parameters Selected: `ARIMA(3, 0, 4)`
- Model Evaluation Metrics:
  - **RMSE:** [108.9]
  - **MAE:** [76.4]

