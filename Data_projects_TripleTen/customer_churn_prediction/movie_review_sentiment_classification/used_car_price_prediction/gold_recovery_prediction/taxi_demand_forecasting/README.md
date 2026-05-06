# Taxi Demand Forecasting — Sweet Lift Taxi

## Project Description

This project focused on forecasting hourly taxi demand at airports. The goal was to help a taxi company predict demand and allocate drivers more effectively.

## Objective

The objective was to build a time series forecasting model that predicts the number of taxi orders for the next hour.

## Tools and Technologies

- Python
- pandas
- NumPy
- scikit-learn
- Time Series Analysis
- Lag Features
- Rolling Mean Features
- TimeSeriesSplit
- RMSE
- Jupyter Notebook

## Methods

The project included the following steps:

1. Loaded and reviewed taxi order data.
2. Converted the time column into a datetime index.
3. Resampled data to hourly order counts.
4. Explored trends, seasonality, and demand patterns.
5. Created lag features and rolling mean features.
6. Prevented data leakage by shifting time-based features.
7. Used time-series-aware validation.
8. Evaluated models using RMSE.

## Results

The project demonstrated how time series feature engineering can be used to forecast hourly demand. The model helped predict periods of higher taxi demand.

## Business Value

A taxi company could use this forecast to better plan driver availability, reduce customer wait times, and improve service during high-demand periods.

## Future Improvements

- Add calendar features such as holidays, weekends, and events.
- Test advanced forecasting models.
- Add weather or flight arrival data.
- Build a dashboard for hourly demand planning.
