# Autoregressive Moving Average (ARMA): Sunspots Data

This repository contains Python code for analyzing the Autoregressive Moving Average (ARMA) model applied to sunspots data. 

## Overview
The ARMA model is used to analyze and forecast time series data. In this case, we're using it to analyze sunspot activity from 1700 to 2008. The data consists of the number of sunspots observed each year.

## Flow
1. **Data Loading**: Load the sunspots data spanning from 1700 to 2008.
2. **Data Visualization**: Visualize the sunspots data to understand its patterns and trends.
3. **Model Fitting**: Fit ARMA models to the sunspots data to analyze and forecast future sunspot activity. 
    - Fit models with different orders to find the best fit for the data.
4. **Model Evaluation**: Evaluate the fitted models using various performance metrics.
    - Check model parameters and evaluation metrics such as AIC, BIC, and HQIC.
    - Test for model fit and normality of residuals.
    - Visualize autocorrelation and partial autocorrelation of residuals.
5. **Dynamic Prediction**: Perform in-sample dynamic prediction to forecast sunspot activity for future years.
6. **Performance Metrics**: Calculate performance metrics to assess the accuracy of the forecasted values.
    - Calculate Mean Forecast Error (or Forecast Bias) to determine the average forecast error.
    - Calculate Mean Absolute Error (MAE) to describe error in the same units as the predictions.
    - Calculate Mean Squared Error (MSE) to assess the average of the squared forecast error values.
    - Calculate Root Mean Squared Error (RMSE) to transform MSE back into the original units of the predictions.

## Performance Metrics
Performance metrics are crucial for evaluating the accuracy of time series forecasts. In this project, we use the following performance metrics:
- **Mean Forecast Error (or Forecast Bias)**: The average of the forecast error values, indicating the tendency of the model to over or under forecast.
- **Mean Absolute Error (MAE)**: The average of the absolute values of the forecast error, providing a measure of the average magnitude of errors.
- **Mean Squared Error (MSE)**: The average of the squared forecast error values, giving more weight to large errors.
- **Root Mean Squared Error (RMSE)**: The square root of the MSE, transforming it back into the original units of the predictions.

These metrics help us understand the accuracy and reliability of our ARMA model in predicting future sunspot activity.

## License
This project is licensed under the BSD 2-Clause License. See the [LICENSE](LICENSE) file for details.

## Contributors
- [mudit2004](https://github.com/mudit2004)

Feel free to contribute by opening issues or pull requests!
