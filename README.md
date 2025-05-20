# Car-Price-Prediction-Model

# 🚗 Car Price Prediction - Capstone Project 3

This repository contains a machine learning project to predict used car prices based on various features. The analysis was conducted as part of a capstone project and includes data cleaning, exploratory data analysis (EDA), feature engineering, and model building.

## 📁 Project Structure

- `Capstone 3 Project Car Price Prediction.ipynb`: The main Jupyter notebook containing the entire workflow.
- `data_saudi_used_cars.csv`: The dataset used for analysis (not uploaded for privacy).
- `README.md`: Project overview and instructions.

## 📊 Dataset Overview

The dataset contains **5624 rows** and **11 columns**, including:

- **Numerical Features**: `Year`, `Engine_Size`, `Mileage`, `Price`
- **Categorical Features**: `Type`, `Region`, `Make`, `Gear_Type`, `Origin`, `Options`
- **Boolean Feature**: `Negotiable`

### Data Notes:
- No missing values, but 4 duplicate rows were identified and removed.
- Some values such as `Mileage > 20,000,000 km` and `Price = 0 or 1 SAR` were treated as potential outliers.

## 🔍 Exploratory Data Analysis (EDA)

EDA focused on identifying:
- Distribution of numerical and categorical variables.
- Relationship between features and the target variable (`Price`).
- Detection of outliers and unusual patterns.
- Correlation between features.

## ⚙️ Modeling Approach

- Data encoding: Label Encoding and One-Hot Encoding applied to categorical features.
- Feature selection: Backward elimination with `statsmodels` to choose significant variables.
- Models explored:
  - Linear Regression
  - Random Forest Regressor
  - XGBoost Regressor
- Model evaluation using RMSE and R² Score.

## 🛠️ Tools & Libraries Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Statsmodels

## 📈 Results

The final model achieved satisfactory performance in predicting used car prices, with XGBoost showing the best generalization capabilities.


By Ridha Shahnabiel Hayat
JCDS 2602, 2025
