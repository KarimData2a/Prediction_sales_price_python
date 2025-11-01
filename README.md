# Prediction_sales_price_python

Main Steps
Exploratory Data Analysis (EDA)
•	Studied the distribution of house sale prices
•	Detected and visualized outliers (boxplots, histograms)
•	Analyzed correlations between numerical variables
•	Visualized main trends using heatmaps and density plots
Data Cleaning and Preparation
•	Handled missing values
•	Encoded categorical variables (One-Hot / dummy encoding)
•	Applied a logarithmic transformation to the target variable to reduce skewness
•	Standardized and aligned training and testing datasets
Modeling and Evaluation
Several regression models were tested to assess their performance and generalization capabilities:
•	Multiple Linear Regression
•	Elastic Net Regression (L1 + L2 regularization)
•	Random Forest Regressor
•	XGBoost Regressor
•	Neural Network (MLP Regressor)
Each model was evaluated using metrics such as MAE, RMSE, and R² to compare their predictive performance.
