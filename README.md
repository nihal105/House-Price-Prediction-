# House-Price-Prediction-Analysis

## Overview

This project focuses on building a predictive machine learning model to estimate house prices using the King County housing dataset. The workflow includes data preprocessing, exploratory analysis, outlier handling, feature scaling, and the implementation of multiple regression algorithms. Three models—Linear Regression, Decision Tree Regressor, and Random Forest Regressor—are trained and evaluated to compare their performance in predicting housing prices. The project demonstrates a complete end-to-end machine learning pipeline, emphasizing both accuracy and interpretability.

## Objectives
* Predict house prices based on various features
* Compare performance of multiple regression algorithms
* Understand the impact of preprocessing and feature scaling
* Identify the best-performing model for accurate predictions
## Dataset
* Source: King County House Sales Dataset (Kaggle)
* Total Records: 21,613
* Features: 21 columns (before preprocessing)
* Includes attributes like:
* Number of bedrooms & bathrooms
* Square footage (living area, lot)
* Grade and condition
* Location-related features
##  Data Preprocessing
* Removed irrelevant columns:
* id (unique identifier)
* date (not directly useful for prediction)
* Checked and confirmed:
* No missing values
* No duplicate data issues
* Outlier handling:
* Used IQR method (3×IQR) to remove extreme price values
* Feature scaling:
* Applied StandardScaler for normalization
## Data split:
* 80% training and 20% testing
##  Exploratory Data Analysis (EDA)
* Performed statistical summary of dataset
* Visualized feature distributions
* Used boxplots to analyze:
* Price vs Bedrooms
* Price vs Grade
* Identified and removed extreme outliers
## Models Implemented
* Linear Regression
* Baseline model
* Assumes linear relationship between features and price
* Fast and interpretable
* Decision Tree Regressor
* Captures non-linear relationships
* Uses rule-based splitting
* No need for feature scaling
* Random Forest Regressor
* Ensemble model (multiple decision trees)
* Reduces overfitting
* Provides higher accuracy and robustness
##  Evaluation Metrics
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score
##  Key Highlights
* Clean and well-preprocessed dataset
* Effective outlier removal improved model performance
* Multiple models compared for better insights
* Demonstrates complete ML pipeline from raw data to prediction
##  Technologies Used
* Python
* NumPy
* Pandas
*  Matplotlib
* Seaborn
* Scikit-learn
##  Conclusion
Machine learning models can effectively predict house prices
Ensemble methods like Random Forest generally perform better
Proper preprocessing and feature handling significantly impact results
## Future Improvements
Hyperparameter tuning for better accuracy
Feature engineering (new derived features)
Use advanced models like XGBoost or Gradient Boosting
Deploy model as a web application
