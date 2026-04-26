# Du-doan-gia-kim-cuong
📌 Project Summary

Developed and evaluated regression models to predict diamond prices using structured data. The project demonstrates end-to-end machine learning workflow including data preprocessing, feature engineering, model training, and performance evaluation.

🎯 Objectives
Predict diamond price (Price) based on physical and categorical attributes
Compare performance of multiple regression models
Improve model generalization using regularization techniques
🧠 Methods & Models
Linear Regression
Ridge Regression (L2 Regularization)
Lasso Regression (L1 Regularization)
📊 Dataset
~54,000 observations, 11 features
Source: Kaggle Diamonds Dataset
Key Features:
Numerical: Carat, Depth, Table
Categorical: Cut, Color, Clarity
Target: Price
⚙️ Data Processing
Removed irrelevant features (Number, X, Y, Z)
Handled missing values:
Dropped missing categorical data
Imputed numerical data using median
Encoded categorical variables
Applied feature scaling
Split dataset: 70% training / 30% testing
