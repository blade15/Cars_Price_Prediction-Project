# 🚗 Used Cars Price Prediction

This project focuses on building a machine learning model that predicts the selling price of used cars based on their attributes such as age, fuel type, transmission, and more. It follows the full data science pipeline from data cleaning to model evaluation.

## 🧠 Problem Statement

Used car pricing can be inconsistent and influenced by various factors. This project aims to help buyers and sellers better understand car valuations by training a predictive model.

### 🔍 Objectives

- Analyze the key factors that affect used car prices.
- Build a regression model to accurately predict a car's selling price.
- Answer key business questions such as:
  - How do age and fuel type affect the price?
  - Which features are most influential?

## 📊 Dataset

The dataset contains records of used cars with features such as:

- Car name
- Present price
- Selling price
- Year of manufacture
- Kilometers driven
- Fuel type
- Seller type
- Transmission type
- Owner history

Make sure the dataset (CSV) is included in the same directory or adjust the path accordingly in the notebook.

## 🔧 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn

## 📈 Workflow Summary

1. **Exploratory Data Analysis (EDA)**:
   - Feature analysis
   - Outlier detection
   - Correlation study

2. **Data Cleaning**:
   - Feature engineering (e.g., calculating car age)
   - Handling categorical variables
   - Dropping irrelevant features

3. **Model Building**:
   - Train-test split
   - Multiple regression models tested (Linear, Ridge, Lasso)
   - Model evaluation using R² Score and RMSE

4. **Model Optimization**:
   - Feature selection
   - Regularization techniques
   - Residual analysis


