# Calories Burnt Prediction

## Project Overview
This project addresses a regression problem to predict the number of calories burnt based on various input features. By applying machine learning techniques, we aim to develop a reliable predictive model. This project includes data preprocessing, exploratory data analysis, and model implementation to achieve high accuracy.

- **Dataset Link**: [Calories Burnt Dataset on Kaggle](https://www.kaggle.com/datasets/fmendes/fmendesdat263xdemos)

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Preprocessing](#data-preprocessing)
3. [Exploratory Data Analysis](#exploratory-data-analysis)
4. [Modeling](#modeling)
5. [Results](#results)
6. [Requirements](#requirements)

## Data Preprocessing
The dataset was prepared using the following steps:
- Handled missing values.
- Removed duplicate rows.
- Corrected data types of features.
- Addressed outliers.
- Transformed categorical features into a numerical format.

## Exploratory Data Analysis
We explored and visualized the data to gain insights, focusing on:
- Distribution of calories in relation to all features.
- Key features affecting calories burnt (e.g., Height, Weight, Body Temperature).
- Distribution of calorie burn by gender, including the percentage in males.
- Correlation between features.

## Modeling
We used two machine learning algorithms for modeling:
- **Random Forest**
- **XGBoost**

Both models were optimized using hyperparameter tuning to improve performance.

## Results
The models achieved a high accuracy rate:
- **Accuracy**: 99%
- **Evaluation Metric**: `mean_squared_error`

This demonstrates the effectiveness of the Random Forest and XGBoost models in accurately predicting calorie burn.

## Requirements
- **Python Version**: 3.x
- **Libraries**:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `xgboost`

---

Feel free to explore the code and experiment with different features or models to further improve the accuracy of calorie burn predictions. Happy coding!
