# Prediction-of-Online-News-Popularity-Using-Regression

The focus of this project is to develop a predictive model using regression techniques to forecast the popularity of online news articles, as measured by the number of shares they receive.

# Data Description
URL: https://archive.ics.uci.edu/ml/datasets/online+news+popularity.

This dataset is from UCI Machine Learning Repository. It contains 59 features and the number of shares for 39644 pieces of news originally collected from www.mashable.com.

# Regression Models
There is the implementation and evaluation of three regression models:
1. Linear Regression
2. Ridge Regression
3. RandomForestRegressor

As I use metrics such as MAE, MSE, and r2 to compare models, I aim to find the best predictor for online news popularity. This helps us refine our strategies and better engage our audience.

# Result

The Random Forest Regressor model emerged as the top performer among those tested, boasting the highest test score R2 and impressive test score MAE. While the Linear Regressor and Ridge Regression models also demonstrated reasonable performance, they fell short of matching the Random Forest Regressor's effectiveness.



