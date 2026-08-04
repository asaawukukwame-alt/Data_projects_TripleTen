# Taxi Demand Forecasting

## Project Description

This project focused on building a time series forecasting model to predict hourly taxi demand.

The goal was to help a taxi company forecast demand so more drivers can be available during high-demand periods.

## Objective

The objective was to build a model that predicts the number of taxi orders for the next hour using historical demand patterns.

## Tools and Technologies

- Python
- pandas
- NumPy
- scikit-learn
- Time series forecasting
- Lag features
- Rolling averages
- Regression modeling
- RMSE
- Jupyter Notebook

## Methods

The project included the following steps:

1. Loaded and reviewed historical taxi order data.
2. Resampled the data by hour.
3. Analyzed demand trends and seasonality.
4. Created lag features and rolling mean features.
5. Split the data using time-based train/test separation.
6. Trained and compared forecasting models.
7. Evaluated model performance using RMSE.

## Results

The project demonstrated how time series features can be used to forecast hourly taxi demand.

The model was evaluated using RMSE to measure the average size of prediction errors.

## Business Value

Taxi demand forecasting can help transportation companies plan driver availability, reduce wait times, and improve customer service during peak demand.

Forecasting demand also helps improve operational efficiency and resource allocation.

## Future Improvements

- Add weather and event data.
- Build a Streamlit forecasting dashboard.
- Test more advanced time series models.
- Add automated retraining.
- Deploy the model as an API.
