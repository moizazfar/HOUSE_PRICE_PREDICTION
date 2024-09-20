# House Price Prediction

This project focuses on predicting house prices using a dataset from Kaggle. The aim is to explore, clean, and model the data to achieve accurate predictions.

## Table of Contents

- [Introduction](#introduction)
- [Data Exploration and Cleaning](#data-exploration-and-cleaning)
- [Feature Engineering](#feature-engineering)
- [Modeling](#modeling)
- [Results](#results)
- [Acknowledgments](#acknowledgments)

## Introduction

The goal of this project is to accurately predict house prices using various machine learning models. The dataset is sourced from [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).

## Data Exploration and Cleaning

- Handled missing values efficiently.
- Transformed skewed data for better distribution.
- Visualized data distributions and correlations to identify key features.

## Feature Engineering

- Encoded categorical features using Label Encoding.
- Selected top features based on correlation with the target variable, `SalePrice`.

## Modeling

We experimented with several models:

1. **Linear Regression**
   - Achieved an accuracy of 89.6%.

2. **Random Forest Regressor**
   - Reached an accuracy of 89.5%.

3. **Gradient Boosting Regressor**
   - Improved to an accuracy of 91.8%.

## Results

- Gradient Boosting Regressor performed the best, showing the importance of feature selection and model choice in predictive accuracy.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
