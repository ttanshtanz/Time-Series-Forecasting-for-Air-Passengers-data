# Time-Series-Forecasting-for-Air-Passengers-data
Time Series Forecasting for Air Passengers data using SARIMA model

## Overview
This repository contains code for time series forecasting using the Seasonal Autoregressive Integrated Moving Average (SARIMA) model. The project involves loading time series data, exploring its properties, checking for stationarity, transforming the data, and building the SARIMA model. The model is then used for forecasting future values of the time series.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Statsmodels
- pmdarima

## Dataset
The dataset used for this project is sourced from the 'AirPassengers.csv' file, containing monthly air passenger counts.

## Workflow

### Data Preprocessing
- Loading and converting the 'Month' column to datetime format.
- Checking for stationarity using the Augmented Dickey Fuller test.
- Decomposing the time series into its components (trend, seasonality, and residual).

### Transformation
- Applying log transformation to stabilize the variance.
- Creating rolling mean and rolling standard deviation plots.

### SARIMA Model
- Determining the order of differencing and identifying the seasonal and non-seasonal components.
- Splitting the data into training and test sets.
- Building and fitting the SARIMA model.

### Forecasting
- Forecasting future values using the trained SARIMA model.
- Comparing the forecasted values with the original time series.

## Results
- SARIMA model outperforms the simple ARIMA model in terms of accuracy.
- Forecasting future values with a 5-year horizon.
