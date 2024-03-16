# wine-quality-prediction
Wine Quality Prediction Model
# Wine Quality Prediction Model

## Project Overview
This project focuses on predicting wine prices based on various features such as winery, wine, year, rating, number of reviews, region, type, body, and acidity. We perform exploratory data analysis (EDA), feature selection, and modeling using Linear Regression, Random Forest, and Lasso Regression.

## Dataset Description
The dataset contains information about wines including their winery, type, year, and physical characteristics like body and acidity. Price is the target variable we aim to predict.

## Exploratory Data Analysis (EDA)
We performed correlation analysis, observed class imbalances in the price data, and applied logarithmic transformation to make the data more suitable for analysis.

## Feature Selection
Feature selection was carried out using the backward stepwise selection method to find the best features based on their importance derived from the Random Forest model.

## Modeling
Three regression models were trained and evaluated:
- Linear Regression
- Random Forest Regressor
- Lasso Regression

Hyperparameters for the Random Forest model were optimized using GridSearchCV.

## Results
The models' performance was evaluated using the Mean Squared Error (MSE) and R-squared value.

## Requirements
- Python 3
- pandas
- scikit-learn
- matplotlib
- seaborn
- numpy


