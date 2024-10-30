# Forecasting Product Sales Using Time Series Analysis Methods

Experimenting with various time series forecasting models to identify the most effective approach for predicting daily sales of a specific product in a store for the upcoming month, using historical data spanning five years.
This machine learning project demonstrates the stages involved in working with time series data, including data analysis and seasonality assessment, model development and accuracy evaluation, and backtesting.

## Project Overview

### Dataset:

Data from Kaggle competition: https://www.kaggle.com/competitions/demand-forecasting-kernels-only/overview
Download dataset from Google Drive: https://drive.google.com/file/d/1F_fr2hseqyz5Xw9B6DF-8HorMqwqkn2N/view?usp=sharing 

### Project Steps

1. **Data Preparation**: Prepare the data for analysis, ensuring it was suitable for modeling.
2. **Time Series Decomposition**: Decompose the time series into its components, assess seasonality, identify significant lags relevant for forecasting.
3. **Feature Engineering**: Enrich the dataset with date-based features to enhance its predictive power.
4. **Model Experimentation**: Conduct experiments with various forecasting models and identify the best model for our specific case.
5. **Backtesting**: Perform backtesting on the best-performing model to evaluate its predictive accuracy on historical data.
 
### Technical Aspects

  Library: statsmodels, darts  
  Algorithms Used: XGBoost, Exponential Smoothing, Prophet, ARIMA, AutoARIMA, RNN  
  Output: The model predicts products sales for 1 month  

