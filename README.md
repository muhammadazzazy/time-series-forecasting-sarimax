# Time-Series Demand Forecasting with SARIMAX

Implementation of SARIMAX models for time series forecasting of merchant demand patterns with performance evaluation metrics.

## Overview
This Jupyter notebook implements time series forecasting using SARIMAX (Seasonal ARIMA with eXogenous variables) models. The analysis includes:

- Data preprocessing and exploration
- Time series decomposition and seasonality analysis
- Model parameter selection using ACF and PACF
- SARIMAX model training and forecasting
- Model evaluation using RMSE, MSE, MAE and Theil's U-statistic
- Residual analysis and diagnostic tests

## Contents
- `QUIK_SARIMAX.ipynb`: Main notebook containing the implementation and analysis

## Requirements
- Python 3.x
- Required packages: pandas, numpy, matplotlib, pmdarima, statsmodels, scipy

Install required package:
```bash
pip install pmdarima
```

Other packages can be installed using:
```bash
pip install pandas numpy matplotlib statsmodels scipy
```
