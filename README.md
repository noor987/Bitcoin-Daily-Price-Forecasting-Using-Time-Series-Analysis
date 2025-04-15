# 📈 Bitcoin Price Forecasting Assignment - 121XXXX_Assignment_4.ipynb

This project explores the use of **time series forecasting models** on **Bitcoin's daily closing price** data. The goal is to compare linear, non-linear, and ARIMA models to predict future prices and determine the most accurate forecasting technique.

---

## 🗂 Assignment Overview

**Assignment Title**: Bitcoin Price Forecasting Using Time Series Models  
**File Submitted**: `121XXXX_Assignment_4.ipynb`  
**Dataset**: `BTC-Daily.csv` (daily Bitcoin prices)  
**Tools Used**: Python, Pandas, Matplotlib, Scikit-learn, Statsmodels

---

## 🎯 Objectives

- Understand and prepare time series data for analysis.
- Apply and compare multiple forecasting models:
  - Linear Regression
  - Non-Linear Regression
  - ARIMA
- Evaluate and interpret the performance of each model.
- Identify the most suitable forecasting method for Bitcoin price prediction.

---

## 📊 Dataset Description

The dataset `BTC-Daily.csv` contains:
- **Date**: Daily timestamps
- **Close**: Daily closing price of Bitcoin
- (May also contain `Open`, `High`, `Low`, `Volume`, etc.)

---

## 📌 Assignment Structure

### 🔹 Part 1: Data Exploration and Preparation
- Load and inspect `BTC-Daily.csv`
- Generate descriptive statistics and date range
- Visualize daily closing prices using line plots
- Handle missing or anomalous data
- Normalize or standardize prices (if required)

### 🔹 Part 2: Building Forecasting Models
#### 📐 Linear Regression
- Convert date to numerical format
- Fit a simple linear regression model
- Evaluate its suitability for financial time series

#### 🧮 Non-Linear Regression
- Explore polynomial regression (or other nonlinear methods)
- Justify choice of model
- Fit and visualize model performance

#### 🔁 ARIMA Model
- Test stationarity using ADF test
- Apply differencing and log transformation
- Analyze ACF and PACF plots
- Select and fit optimal ARIMA(p,d,q) model
- Summarize results

---

## 📈 Evaluation and Metrics

Each model is evaluated using:
- **RMSE** (Root Mean Square Error)
- **MAE** (Mean Absolute Error)
- **MAPE** (Mean Absolute Percentage Error)

Validation:
- Time Series Cross-Validation (Rolling Forecast Origin)
- Residual analysis to check for model assumptions and patterns

---

## ⚖️ Comparative Analysis

- Comparison of model strengths and weaknesses
- Visual and statistical comparison of residuals and predictions
- Justification of the **best-performing model**
