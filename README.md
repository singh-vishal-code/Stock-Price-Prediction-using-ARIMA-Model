# Stock-Price-Prediction-using-ARIMA-Model

This project implements the ARIMA (AutoRegressive Integrated Moving Average) model to forecast stock prices based on historical time series data. The goal is to build an accurate predictive model for stock closing prices.

**Objectives**
Fetch and visualize historical stock price data.
Perform stationarity tests (ADF Test) and apply differencing if required.
Identify optimal ARIMA(p,d,q) parameters using ACF/PACF plots and AIC/BIC.
Fit the ARIMA model and forecast future stock prices.
Compare actual vs. predicted prices using evaluation metrics.

**Technologies Used**
Python
Pandas, NumPy – Data processing
Matplotlib, Seaborn – Visualization
Statsmodels – ARIMA modeling
yfinance – Fetch stock data
Jupyter Notebook – Analysis environment

**Key Steps**
1. Data Collection
   Download historical stock price data using yfinance.
2. Time Series Analysis
   Plot the stock price trend.
   Test for stationarity using Augmented Dickey-Fuller (ADF) test.
3. Model Selection
   Analyze ACF and PACF plots to determine p and q.
   Use Auto ARIMA or manual tuning for parameter selection.
4. Model Training & Forecasting
   Train ARIMA model on historical data.
   Generate future price forecasts and visualize results

5. Performance Evaluation
6. Metrics: RMSE, MAPE, MAE.

**Expected Outputs**
A plot comparing actual vs. predicted stock prices.
Forecasted prices for the next N days.
Model summary with ARIMA coefficients.
