# BTC-USD-Price-Prediction-Using-Machine-Learning

This project focuses on forecasting the **Bitcoin (BTC-USD) price** using historical market data and a **time series forecasting approach** based on Facebook Prophet.

The goal is to analyze past Bitcoin price movements and generate future price predictions in a data-driven and interpretable way.

---

##  Project Overview

- **Asset:** Bitcoin (BTC-USD)
- **Data Source:** Yahoo Finance
- **Model:** Facebook Prophet
- **Approach:** Time Series Forecasting
- **Language:** Python
- **Environment:** Jupyter Notebook

---

##  Dataset

Historical Bitcoin price data is retrieved using the `yfinance` library.

- Start Date: `2000-01-01`
- End Date: `2026-10-02`
- Target Variable: **Closing Price (Close)**

The dataset is automatically downloaded and does not require manual CSV files.

---

##  Methodology

1. Download BTC-USD historical data using Yahoo Finance  
2. Select the **closing price** as the target variable  
3. Preprocess data to match Prophet format:  
   - `ds` → Date  
   - `y` → Target value (BTC closing price)  
4. Train a Prophet time series forecasting model  
5. Generate future predictions  
6. Visualize forecast results and trend components  

---

##  Technologies & Libraries

- Python  
- Prophet  
- yfinance  
- pandas  
- numpy  
- matplotlib  

---

## Results

The model produces future BTC-USD price forecasts based on historical trends.
Prophet decomposes the time series into:
-Trend
-Seasonality
-Residual components
The generated visualizations help interpret long-term movements and potential future behavior of Bitcoin prices.

## Disclaimer

This project is for educational and research purposes only.
It does not constitute financial or investment advice.
  

