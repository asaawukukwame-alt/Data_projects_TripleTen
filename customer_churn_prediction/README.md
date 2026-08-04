# Customer Churn Prediction — Interconnect Telecom

## Project Description

This project focused on building a machine learning model to predict whether telecom customers are likely to churn. The goal was to help the company identify high-risk customers and support customer retention strategies.

## Objective

The objective was to create a classification model that predicts customer churn using contract, personal, phone, and internet service data.

## Tools and Technologies

- Python
- pandas
- NumPy
- scikit-learn
- CatBoost
- LightGBM
- Matplotlib
- Jupyter Notebook
- AUC-ROC
- Accuracy
- Feature Engineering
- Classification Modeling

## Methods

The project included the following steps:

1. Loaded and reviewed multiple telecom datasets.
2. Merged contract, personal, phone, and internet data into one customer-level dataset.
3. Cleaned missing values and prepared features for modeling.
4. Created the churn target variable.
5. Checked for data leakage and removed future-looking information.
6. Trained and compared multiple classification models.
7. Selected CatBoost as the final model based on performance.
8. Evaluated the final model on the test set.

## Results

The final CatBoost model achieved:

- Test AUC-ROC: 0.9731
- Test Accuracy: 0.9307

These results show that the model was able to strongly separate customers who were likely to churn from customers who were likely to stay.

## Business Value

This model can help a telecom company identify customers at higher risk of leaving. The business could use these predictions to prioritize retention campaigns, improve customer service outreach, and reduce churn-related revenue loss.

## Future Improvements

- Improve customer segmentation to understand churn patterns by customer group.
- Add more behavioral features if available.
- Test additional model explainability tools such as SHAP.
- Create a dashboard to help business teams monitor churn risk.
