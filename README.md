# Predictive Analytics Using Historical Data

Data Analytics Internship Project by Anshika Sharma

## Objective
Build a predictive model to forecast future sales trends using historical data.

## What I did
- Cleaned the data (duplicates, missing values, outliers)
- Analysed trend and seasonality
- Built 5 models: Baseline, Linear Regression, Random Forest, Holt-Winters and SARIMA
- Evaluated them with MAE, RMSE, MAPE and R2 on the last 24 months
- Forecasted the next 12 months

## Results
Holt-Winters had the lowest error, followed by SARIMA, then Linear Regression.
Random Forest performed worst because tree models cannot extrapolate a strong upward trend.

## Files
- Predictive_Analytics_Project.ipynb : main notebook
- sales_data.csv : dataset (synthetic monthly sales data, 2015-2023)
- requirements.txt : libraries needed

## How to run
pip install -r requirements.txt
jupyter notebook

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SciPy, Statsmodels
