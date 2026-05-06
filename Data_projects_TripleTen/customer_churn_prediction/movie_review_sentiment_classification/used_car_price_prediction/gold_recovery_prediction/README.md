# Gold Recovery Prediction — Mining Process Optimization

## Project Description

This project focused on predicting gold recovery rates during an industrial mining process. The goal was to support process optimization by modeling rougher and final recovery outcomes.

## Objective

The objective was to build regression models that predict gold recovery using production-stage data and custom evaluation metrics.

## Tools and Technologies

- Python
- pandas
- NumPy
- scikit-learn
- Matplotlib
- Regression Models
- Cross-Validation
- Custom sMAPE Metric
- Jupyter Notebook

## Methods

The project included the following steps:

1. Loaded training, test, and full datasets.
2. Verified the gold recovery calculation.
3. Compared available features across train and test datasets.
4. Analyzed how metal concentrations changed across purification stages.
5. Compared feed particle size distributions between training and test samples.
6. Investigated total concentration distributions to identify anomalies.
7. Built a custom sMAPE metric.
8. Trained and evaluated regression models using cross-validation.

## Results

The project demonstrated how regression models can be used to predict industrial recovery outcomes. The analysis also helped identify data quality issues and process-stage patterns that could affect model performance.

## Business Value

A mining company could use this type of model to improve process monitoring, estimate recovery outcomes, reduce waste, and support operational decision-making.

## Future Improvements

- Test more advanced regression models.
- Add more process control features.
- Improve anomaly detection before training.
- Create a monitoring dashboard for recovery predictions.
