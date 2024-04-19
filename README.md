# Wine Connoisseurs

## This is a read me file

#### Kaggle Links/Dataset Used:
- https://www.kaggle.com/datasets/budnyak/wine-rating-and-price

#### Problem Statement: 
To help businesses or consumers to determine rating and price of wine based on the characteristics of the wine

#### Data Processing:
1. Cleaned data - Extreme Prices using IQR, removed data without 'Year' Information
2. Predict Rating based on Year, Wine Type and Country
3. Combine Predicted Rating from 2. to test dataset of 4.
4. Predict Price Based on Year, Wine Type, Country and Predicted Rating.
5. Analysis

#### Models used: Linear Regression, Tree Regression, Gradient Boosting Regression

#### Best Model: Gradient Boosting (Lowest MSE & Highest Explained Variance)

#### Limitations: Generalizability 

#### Learnings: One-hot Encoding, Double Prediction, Tree Regression, Gradient Boosting Regression
