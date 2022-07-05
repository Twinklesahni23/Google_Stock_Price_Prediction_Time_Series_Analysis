# Google_Stock_Price_Prediction_Time_Series_Analysis

![Green Simple Professional LinkedIn Banner----](https://user-images.githubusercontent.com/99166745/177326636-7f8ce7bc-37ee-40f3-814f-ccf2232a3b70.png)

*In this project, I have attempted to predict the stock price of Alphabet Inc., the parent company of GOOGLE for next 30 days using SARIMA Model.*

I have also implemented ARIMA model on the dataset to express the difference between ARIMA and SARIMA models. Broadly, the SARIMA captures the seasonality in the data which can be attributed as a characteristic of a time series in which the data experiences regular and predictable changes that recur at specific intervals and thus is able to produce better results in our analysis.

The dataset contains open, high, low, close, adjusted close prices and volume of the stock from June 30, 2021 to June 29, 2022 which is taken from Yahoo Finance.
## Table of Contents
1. Loading and Reading the Dataset
   * Explanatory Data Analysis
2. Data Visualization 
   * Plotting the Candlestick Chart
   * Plotting the Closing Price against Years
   * Plotting the Kernel Density Estimate (KDE) Chart
3. Stationarity
   * Augmented Dickey Fuller (ADF) Test
   * Plotting the rolling statistcs against original series
   * Transforimg the Series
     * First Differencing
     * Seasonal Decomposition
4. ACF and PACF
5. Training and Testing Data
6. ARIMA Model
   * Building the Model
   * Predictions
7. SARIMA Model
   * Building the Model
   * Predictions
   * Forecasting price for next 30 days
   
## Insights from the analysis

**Price Movement and Volume traded during last one year**
![newplot](https://user-images.githubusercontent.com/99166745/177274597-104d679a-5d7e-44ca-810c-670c5368fa66.png)

**Result of ARIMA Model: Clearly, ARIMA Model failed to capture the data pattern and thus produced largely inaccurate predictions.**

![image](https://user-images.githubusercontent.com/99166745/177276937-fb6adb67-6ec1-4697-a50e-e2b880c72294.png)

**Result of SARIMA Model: Here, the seasonal factor is accounted by the model and it is for this feature that our model has produced such accurate predictions**

![image](https://user-images.githubusercontent.com/99166745/177285085-901f7a9e-28c4-4970-b321-2e44e728ae72.png)

**Forecasted Price for next 30 days**

![image](https://user-images.githubusercontent.com/99166745/177284903-3f6b6332-b888-4067-964e-12d5d2b2847b.png)

