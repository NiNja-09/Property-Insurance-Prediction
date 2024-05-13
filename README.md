# Property Insurance Premium Prediction

![banner-home-insurance-1 (3)](https://github.com/ninadpatil09/Property-Insurance-Premium-Prediction/assets/60342946/856354d6-3a04-49b1-9a3a-c9bb667aa1fa)

## Overview
This project aims to predict property insurance premiums using machine learning techniques. The dataset consists of various features related to insurance policies and properties. The goal is to build models that can accurately predict the annual premium based on these features.

It focuses on predicting property insurance premiums, specifically targeting home insurance premiums. Property insurance plays a crucial role in safeguarding homeowners against financial loss due to unforeseen events such as natural disasters, accidents, or theft. Accurately predicting insurance premiums is essential for insurance companies to appropriately price their policies and for homeowners to make informed decisions about their coverage.


## Data Preprocessing
  - Handling Missing Values: Rows with missing values in certain columns were dropped. Missing values in other columns were imputed using appropriate methods.
  - Feature Engineering: New features such as client age and property age were created based on existing date columns.
  - Encoding Categorical Variables: Categorical variables were encoded using one-hot encoding.
  - Standardizing Numerical Features: Numerical features were standardized to bring them to a similar scale.

## Model Training
Several regression models were trained and evaluated for their performance in predicting insurance premiums:
- Decision Tree Regression
 - Support Vector Regression (SVR)
 - Gradient Boosting Regression
 - Random Forest Regression
 - XGBoost Regression
 - LightGBM Regression

## Model Evaluation
The performance of each model was evaluated using the following metrics:
 - Mean Absolute Error (MAE)
 - Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
 - R-squared Score (R^2)

## Results
Among the models evaluated, XGBoost and LightGBM demonstrated the best performance in terms of lower MAE, MSE, RMSE, and higher R^2 score. Further, hyperparameter tuning using grid search and cross-validation was performed for XGBoost and LightGBM, resulting in improved performance.

## Conclusion
This project illustrates the utilization of machine learning methods for the prediction of property insurance premiums. The top-performing models, namely XGBoost and LightGBM, exhibit strong potential in assisting insurance firms to precisely predict insurance premiums, thereby refining risk evaluation and pricing strategies.

Estimating property insurance premiums, particularly for home insurance, is a pivotal undertaking involving comprehensive analysis of diverse factors to ensure accurate coverage cost assessment. By harnessing machine learning methodologies and adept data analysis, insurance enterprises can optimize their pricing strategies, offering competitive premiums while maintaining adequate coverage for homeowners.
