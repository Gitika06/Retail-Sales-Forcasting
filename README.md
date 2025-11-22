# Retail Sales Forecasting using Time Series Analysis

## Project Overview
This project builds a forecasting model using ARIMA to predict the next 30 days of retail sales. The dataset includes Date and Sales values, and preprocessing ensures proper time-series structure.

## Features
- Clean and preprocess sales dataset  
- Convert Date column to datetime format  
- Set Date as index for time-series modeling  
- Perform stationarity checks (ADF Test)  
- Build ARIMA model  
- Forecast next 30 days  
- Visualize historical vs forecasted sales  

## Techniques Used
- Exploratory Data Analysis (EDA)
- Time Series Analysis
- ARIMA Model
- Trend + Forecast Visualization

## Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Statsmodels

## Dataset
- Columns: Index (unnamed), Date, Sales  
- Date column is set as index during preprocessing  
- Dataset used: Salescsv  

## How to Run
1. Clone the repository  
2. Open the notebook in Google Colab or Jupyter  
3. Upload your CSV file  
4. Run cells in order  

## Output
- Line chart of historical sales  
- Next 30 days forecast visualized in orange
