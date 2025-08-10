## WeatherForecasting-LSTM-Prophet-
## Using live data API- Metostat based weather forecasting project

# Weather Forecasting Project Using Prophet and LSTM

This project focuses on forecasting temperature using historical and live weather data. It combines traditional time series forecasting (Prophet) and deep learning (LSTM) models to predict weather with improved accuracy.

---

## 🚀 Project Overview

- Collects and preprocesses temperature data from global weather APIs or repositories.
- Implements two forecasting models:
  - **Prophet:** Facebook’s time series model for trend and seasonality.
  - **LSTM:** Deep learning model capturing temporal dependencies.
- Compares models using metrics like MAE, RMSE, MAPE, and statistical tests (Diebold-Mariano).
- Performs backtesting and residual diagnostics for robustness.
- Visualizes forecasts, residuals, and prediction intervals.
- Demonstrates superior performance of LSTM over Prophet for temperature prediction.

---

## 🛠️ Features

- Data ingestion and cleaning from live API feeds or static datasets.
- Scaling and windowing for LSTM sequence preparation.
- Model training and evaluation with detailed metrics.
- Statistical significance testing between models.
- Prediction interval calculation and coverage analysis.
- Visualization of actual vs predicted values and error distributions.
- Backtesting to simulate real-world forecasting performance.

---

## 📊 Results Summary

- LSTM outperforms Prophet in all key metrics (MAE, RMSE, MAPE).
- Diebold-Mariano test confirms statistically significant forecast improvement.
- Residual diagnostics indicate LSTM residuals approximate white noise, suggesting better fit.
- Prediction intervals show good coverage (around 91% for both models).
- Backtesting demonstrates consistent LSTM performance across multiple time windows.

---

## 🧰 Requirements

- Python 3.x
- Libraries: pandas, numpy, matplotlib, scikit-learn, tensorflow, keras, prophet, statsmodels
- Access to weather data API or local datasets

---

# google collab link: https://colab.research.google.com/drive/1jqUTILMPobJjW1AtfRvLW0OCpJjZvdvU?usp=sharing

# Project report : https://drive.google.com/file/d/1BbMElk8xYE2qRHqGWFtljcnF7XygWHNV/view?usp=sharing

