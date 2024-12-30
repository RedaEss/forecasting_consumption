# Electricity Consumption Analysis and Forecasting 🌟⚡

This repository contains an analysis and forecasting of electricity consumption using historical data. The goal is to gain insights into electricity usage patterns, identify trends, and make accurate forecasts to optimize energy management.

## Dataset

The dataset used in this analysis is from the [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption), specifically:

- Hebrail, G. & Berard, A. (2006). Individual Household Electric Power Consumption [Dataset]. UCI Machine Learning Repository. [https://doi.org/10.24432/C58K54](https://doi.org/10.24432/C58K54).

## Steps Involved:

### 1. Data Collection and Preparation
- **Download and load dataset**: The dataset is sourced from the UCI Machine Learning Repository. It contains household electricity consumption data, with measurements taken every minute.
- **Data cleaning**: Handle missing values through interpolation and ensure the dataset is ready for analysis.

### 2. Data Cleaning and Transformation
- **Handle missing values**: Missing values are filled using forward-fill interpolation.
- **Aggregation**: Data is aggregated to monthly electricity consumption metrics.

### 3. Data Visualization
- **Density plots**: Visualize the distribution of original vs. interpolated electricity usage.
- **Monthly consumption trends**: Plot the total electricity usage for each month to uncover seasonal patterns and trends.

### 4. Seasonal Decomposition
- **Time Series Decomposition**: Decompose the time series data into three components: trend, seasonality, and residuals.
- **Visualization**: Plot these components to better understand underlying patterns and anomalies.

### 5. Forecasting with Exponential Smoothing
- **Train forecasting model**: Use the Exponential Smoothing method to forecast future electricity usage based on historical data.
- **Model evaluation**: Visualize and evaluate the model performance with both observed and forecasted values.

### 6. Confidence Intervals
- **Calculate confidence intervals**: Estimate 80% and 95% confidence intervals for future electricity usage.
- **Visualize uncertainty**: Display these confidence intervals alongside forecasted values to understand the range of possible outcomes.

### 7. Interactive Dashboard
- **Create an interactive dashboard**: Use Plotly to develop an interactive visualization for dynamic exploration of electricity consumption patterns and forecasts.


