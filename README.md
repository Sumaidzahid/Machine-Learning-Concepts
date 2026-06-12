# Vehicle Advert Price Prediction

An end-to-end machine learning regression project developed in a Google Colab environment. The notebook focuses on predicting vehicle advertisement prices using structured data preprocessing, exploratory analysis, feature engineering, and model evaluation techniques.

## Project Overview

This project implements a complete machine learning workflow for predicting vehicle prices. It includes data cleaning, feature transformation, encoding strategies for mixed data types, model training, and performance evaluation using regression metrics.

The dataset is processed to handle missing values, outliers, and skewed distributions, followed by comparison of multiple regression models to identify the best-performing approach.

## Key Features

### Data Preprocessing

* Exploratory Data Analysis (EDA) for understanding data distribution
* Handling missing values using imputation techniques
* Outlier detection and treatment
* Log transformation of target variable (price) to reduce skewness

### Feature Engineering

* Mixed feature encoding strategies:

  * One-Hot Encoding for nominal categorical variables
  * Ordinal Encoding for ordered categories
  * Target Encoding for high-cardinality features
* Feature transformation using `ColumnTransformer`

### Machine Learning Models

* Linear Regression
* Decision Tree Regressor
* K-Nearest Neighbors (KNN)

### Model Evaluation

* R² Score (coefficient of determination)
* Mean Absolute Error (MAE)
* Residual analysis
* Error distribution visualizations

## Tools & Technologies

* Python
* Pandas & NumPy
* Scikit-learn
* Matplotlib & Seaborn
* Google Colab
* Machine Learning Regression Techniques

## Workflow Summary

1. Load and inspect dataset
2. Perform EDA and data cleaning
3. Handle missing values and outliers
4. Apply feature encoding and transformations
5. Train multiple regression models
6. Evaluate performance using metrics and visualizations
7. Compare models and interpret results

## Results

The project demonstrates how preprocessing and feature engineering significantly impact regression performance. Multiple models are compared to determine the most suitable approach for predicting vehicle advertisement prices.

## Author

Muhammad Zahid
MSc Artificial Intelligence | Mechatronics Engineer

## Association 

Univesity project: Manchester metropolitan university (mmu)
