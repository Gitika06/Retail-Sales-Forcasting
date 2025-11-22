Retail Sales Forecasting Using Time Series (ARIMA)
Project Overview

This project builds a 30-day sales forecast using time-series analysis (ARIMA).
The goal is to understand historical sales patterns and predict future demand for better business planning.

Dataset
The dataset contains the following columns:
Index (Unnamed column)
Date
Sales
Note: Your Date column is converted into a DateTime index during preprocessing.

Project Workflow
Data Loading
Upload dataset using Google Colab’s files.upload()
Load CSV into a DataFrame

Data Cleaning
Remove unnamed index column
Convert Date to datetime
Set Date as index
Resample to daily frequency (if needed)

Exploratory Analysis (EDA)
Plot historical sales
Check trends and seasonality

ARIMA Modeling
Fit ARIMA/SARIMA model
Evaluate model residuals
Generate future predictions for 30 days

Forecast Visualization
Blue line → Historical sales
Orange line → Next 30-day predicted sales

Results
The ARIMA model successfully predicts future sales based on historical behavior.
Visualization clearly shows the upcoming 30-day trend.

Tech Stack
Python
Pandas
Matplotlib
Statsmodels
Google Colab
