# Gold Recovery Prediction

## Project Description

This project focused on building a machine learning model to predict gold recovery from industrial processing data.

The goal was to help estimate recovery outcomes at different production stages and support more efficient mining operations.

## Objective

The objective was to train and evaluate regression models that predict gold recovery using process-stage data.

## Tools and Technologies

- Python
- pandas
- NumPy
- scikit-learn
- Regression modeling
- Random Forest
- Linear Regression
- Custom evaluation metric
- sMAPE
- Data preprocessing
- Jupyter Notebook

## Methods

The project included the following steps:

1. Loaded and reviewed training, test, and full datasets.
2. Checked data quality and handled missing values.
3. Verified recovery calculations.
4. Analyzed feature differences between datasets.
5. Prepared features for modeling.
6. Trained and compared regression models.
7. Evaluated models using a custom sMAPE metric.
8. Selected the strongest model based on final weighted performance.

## Results

The project demonstrated how machine learning can be used with industrial process data to predict gold recovery outcomes.

The final model was evaluated using a weighted sMAPE score, combining rougher-stage and final-stage recovery performance.

## Business Value

Gold recovery prediction can help mining and production teams estimate process efficiency, identify weak points, and make better operational decisions.

This type of modeling supports cost reduction, production planning, and quality control in industrial environments.

## Future Improvements

- Add process monitoring dashboards.
- Explore additional feature engineering from production-stage data.
- Test more advanced boosting models.
- Add model explainability for key recovery drivers.
- Build a production-style pipeline for repeat evaluation.
