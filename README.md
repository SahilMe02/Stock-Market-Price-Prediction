# Stock-Market-Price-Prediction
Predicts stock prices using machine learning models like Random Forest and XGBoost. Covers data collection, preprocessing, model training, tuning, and evaluation to identify the most accurate model for financial forecasting.


This project focuses on predicting stock prices using ensemble learning models such as Random Forest and XGBoost.
It was developed as part of a postgraduate coursework project to analyze which model performs more accurately for forecasting stock trends based on historical data.


** Overview **
The notebook collects historical stock data from Yahoo Finance, processes it, and trains two regression models to predict future prices.
Both models are evaluated on multiple metrics, including R², MAE, and RMSE, to compare their accuracy and generalization performance.


** Models Used **
Random Forest Regressor (with Out-of-Bag score validation)
XGBoost Regressor (with early stopping and hyperparameter tuning using RandomizedSearchCV)


** Technology Stack **
Python (Jupyter Notebook)
scikit-learn
XGBoost
pandas, numpy
matplotlib, seaborn
yFinance


** Project Workflow **
Data Collection – Fetching stock data from Yahoo Finance using yfinance.
Data Preprocessing – Cleaning, feature scaling, and preparing data for time-based modeling.
Model Training – Training Random Forest and XGBoost models on historical stock data.
Hyperparameter Tuning – Optimizing both models using RandomizedSearchCV.
Evaluation – Measuring R², MAE, and RMSE to compare model performance.
Visualization – Plotting predicted vs actual values and analyzing feature importance.


** Results **
Metric	Random Forest	XGBoost
R² (Test Set)	Slightly higher	Slightly lower
MAE / RMSE	Lower	Marginally higher
The Random Forest model performed slightly better overall in terms of accuracy and consistency on test data.
