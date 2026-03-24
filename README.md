# Monthly-Price-Forecasting-using-SARIMA-
Time series forecasting of monthly prices using SARIMA with data preprocessing, trend &amp; seasonality analysis, and model evaluation using MAE, RMSE, and MAPE.
Monthly Price Forecasting using SARIMA

Project Overview
This project focuses on forecasting monthly prices using time series analysis. A SARIMA (Seasonal AutoRegressive Integrated Moving Average) model is used to capture both trend and seasonal patterns in historical data.

The goal of this project is to predict future price trends based on past observations and support data-driven decision making.

Features
- Time series data preprocessing and cleaning
- Handling missing values using forward fill
- Outlier detection using IQR method
- Trend and seasonality analysis using decomposition
- SARIMA model implementation for forecasting
- Model evaluation using MAE, RMSE, and MAPE
- 12-month future price prediction

Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels

Dataset
- Monthly price data
- Total records: ~197 after cleaning
- Time span: ~16 years

Project Workflow
1. Data Loading
2. Data Cleaning
   - Convert date column
   - Remove duplicates
   - Handle missing values
   - Outlier treatment (IQR)
3. Exploratory Data Analysis (EDA)
   - Time series visualization
   - Decomposition (trend + seasonality)
4. Model Building
   - SARIMA (p,d,q)(P,D,Q,s)
5. Model Evaluation
   - MAE
   - RMSE
   - MAPE
6. Forecasting
   - Predict next 12 months

Model Details
SARIMA parameters used:
- Order: (1,1,1)
- Seasonal Order: (1,1,1,12)

Results
The model successfully captured trend and seasonal patterns and generated future forecasts for 12 months.

Installation
pip install pandas numpy matplotlib statsmodels

otlib statsmodels
