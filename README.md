# House-Prices-Prediction
Predicting House prices using different Regression techniques
This dataset is taken from Kaggle(https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

Data contains of 1460 rows and 81 columns as different features of house. Based on this, we have to predict the House prices.
The Jupyter notebook contains the following contents:
**Exploratory Data Analysis using:**
- Histograms
- Boxplots
- Scatterplots
- Heatmaps

**Data Processing & Feature Engineering** 
- Handling of Categorical, Datetime and Numerical Features
-  Missing values Imputation with different strategies
- Outlier Removal using Percentiles
- Tried different Scaling methods like Log transform, Standard Scaler and Min Max scaler and choosing the best among them.
- Encoding of categorical features

**Feature Selection**
Selected important features using Lasso Regression

**Model Training and Selection**
Tried 3 different models with hyperparameter Tuning: 
- Random forest
- XGBoost Regressor
- Neural network

**Error Metric**
Least Mean Absolute Error was observed with Random Forest

