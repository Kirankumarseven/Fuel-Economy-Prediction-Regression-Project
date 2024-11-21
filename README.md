# Fuel Economy Prediction Project-Regression

This project involved building a machine learning model to predict fuel economy (measured in miles per gallon or MPG) based on vehicle attributes. By utilizing linear regression and regularization techniques (Lasso and Ridge Regression), the project aimed to identify key factors influencing fuel efficiency and provide a reliable prediction model.

## Objectives
Develop a regression model to predict a vehicle's fuel economy.
Compare the performance of Linear Regression, Lasso, and Ridge Regression to handle multicollinearity and feature selection.
Provide actionable insights into the relationship between vehicle features and fuel efficiency.
Dataset
## The dataset included features such as:

Engine size (displacement)
Horsepower
Weight
Number of cylinders
Model year
Fuel type
The data was preprocessed to ensure quality and prepared for regression analysis.

## Steps Undertaken
### 1. Data Preprocessing
Handled missing values and removed outliers for cleaner data.
Normalized numerical features to ensure uniform scaling.
Encoded categorical variables like fuel type and drive type using one-hot encoding.
### 2. Exploratory Data Analysis (EDA)
Explored the relationships between features and MPG using visualizations.
Observed negative correlations between fuel economy and variables like weight and horsepower.
Identified positive trends with newer model years and hybrid technologies.
### 3. Model Development
Linear Regression: Built a baseline model to understand the relationship between predictors and MPG.
Lasso Regression: Applied L1 regularization to perform feature selection and reduce overfitting.
Ridge Regression: Used L2 regularization to address multicollinearity and improve model stability.
### 4. Model Evaluation
Evaluated models using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score.
Compared the models' performance, with Ridge Regression achieving the best balance of accuracy and generalization.
Tools and Technologies Used
Programming Language: Python
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## Key Insights
Vehicle weight and engine size were the most significant predictors, with heavier and larger-engine vehicles showing lower MPG.
Lasso Regression effectively reduced the influence of less important features, streamlining the model without sacrificing accuracy.
Ridge Regression performed best by addressing multicollinearity, providing a stable and interpretable model.
Impact and Applications

## This project delivers actionable insights for:

Automobile Manufacturers: Design vehicles with improved weight-to-power ratios for better fuel efficiency.
Consumers: Choose vehicles optimized for fuel efficiency to reduce costs.
Policy-Makers: Promote standards for eco-friendly and fuel-efficient vehicles.
By employing advanced regression techniques, this project contributes to understanding and predicting fuel economy, aiding in sustainable automotive development.
