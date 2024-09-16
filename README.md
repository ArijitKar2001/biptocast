# Bitcoin Price Prediction using Machine Learning

## Overview

This project aims to predict Bitcoin prices using historical data. We have employed several machine learning techniques, including data processing, feature engineering, and model building to identify the best model for predicting Bitcoin prices. The models used include XGBoost, K-Nearest Neighbors (KNN), Linear Regression, and Random Forest.

## Dataset

The dataset used in this project includes historical Bitcoin price data. It contains features such as:
- Timestamp
- Open Price
- High Price
- Low Price
- Close Price
- Volume
- Currency
- Weighted Price

## Data Processing

1. **Loading Data:** The data is loaded from CSV files and converted into DataFrames.
2. **Handling Missing Values:** Missing values are handled using imputation techniques.
3. **Data Normalization:** The data is normalized to bring all features to a common scale.

## Feature Engineering

1. **Feature Extraction:** Relevant features such as rolling averages and volatility indicators are extracted.
2. **Feature Selection:** Feature selection techniques are applied to choose the most significant features for modelling.

## Stationarity Check

To ensure that our time series data is suitable for modelling, we performed a stationarity check using the Augmented Dickey-Fuller (ADF) test.
## Model Building

We built and evaluated several machine learning models:

1. **Linear Regression:** A baseline model to understand the linear relationships in the data.
2. **K-Nearest Neighbors (KNN):** A non-parametric model to capture local patterns in the data.
3. **Random Forest:** An ensemble method to improve prediction accuracy by averaging multiple decision trees.
4. **XGBoost:** A gradient boosting model to leverage boosting techniques for improved performance.

## Model Evaluation

The models were evaluated based on various metrics. The model with the best performance on the validation set was selected as the final model.
