# Time Series Analysis of Temperature and House Prices in the Midlands

## 📌 Overview

This project is part of my MSc Data Science coursework, focusing on time series analysis using ARIMA models. The study investigates:

- **Annual Temperature Trends (1900-2021)** in the Midlands region of England.
- **Monthly House Prices (2010-2020)** in the East Midlands, with forecasts for the first six months of 2020.

The analysis aims to uncover trends, stationarity, and optimal ARIMA models for forecasting.

## 📊 Data

The datasets used in this project are:

1. **Temperature Data:** Annual average temperature from 1900 to 2021.
2. **House Price Data:** Monthly average house prices from January 2010 to December 2019.

## 🛠️ Methodology

The following steps were carried out for both datasets:

### 1️⃣ Data Exploration

- Time series visualization.
- Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) analysis.

### 2️⃣ Stationarity Checks

- Analyzing trends and seasonality.
- Differencing the series to achieve stationarity.

### 3️⃣ Model Selection

- Evaluating different ARIMA and SARIMA models.
- Using AIC values and statistical hypothesis tests to select the best-fit model.

### 4️⃣ Model Evaluation

- Residual analysis to check for white noise.
- Ljung-Box test for independence.

### 5️⃣ Forecasting

- Predicting future values with confidence intervals.

## 🔍 Key Results

### 📌 Temperature Analysis

- The best-fitting model was **ARIMA(0,1,1)**, capturing the increasing trend over time.
- The residuals indicated a good model fit with white noise properties.

### 📌 House Price Forecasting

- The best model was **ARIMA(1,1,2) × (0,1,1)[12]**, incorporating both trend and seasonality.
- Forecasts for 2020 show continued increase, with prediction intervals at 80% and 95% confidence levels.

## 🚀 How to Run the Analysis

### Requirements

- R programming environment

- Required libraries: forecast, tseries

### Steps

1. Clone the repository:
   ```sh
   git clone https://github.com/EmaanBashir/Timeseries-Analysis-and-Forecasting.git
   cd Timeseries-Analysis-and-Forecasting
   ```
2. Load the dataset files.
3. Run the provided R scripts for analysis and visualization.
4. View the outputs, including plots and forecasts.

## 📷 Visualizations

### Temperature Trend

![image](https://github.com/user-attachments/assets/98cd10fa-9725-4a0a-ad79-8c0a7760ba83)

&#x20;*Figure 1: Temperature time series plot (1900-2021)*

### House Price Forecast

![image](https://github.com/user-attachments/assets/430fc6e7-e1f6-4784-88d6-d87302d9cf9e)

&#x20;*Figure 2: Forecasted house prices for first 6 months of 2020*

## 🎯 Conclusion

This project demonstrates how time series analysis can be applied to real-world datasets for forecasting trends. The results provide insights into long-term temperature changes and housing market trends in the Midlands.

---

For further details, check the full **Report.pdf** included in the repository.

