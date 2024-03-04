# Autocorrelation and Partial Autocorrelation Analysis

This repository contains Python code and explanations for analyzing autocorrelation and partial autocorrelation functions of time series data. It includes insights into autocorrelation, partial autocorrelation functions, ARMA models, and their applications in forecasting.

## Aim

The aim of this project is to understand and apply techniques related to autocorrelation, partial autocorrelation functions, ARMA models, and their applications in time series analysis and forecasting projects.

## Contributor

- **mudit2004**

## License

This project is licensed under the BSD-2 License.

## Dataset

The analysis is performed on the Minimum Daily Temperatures Dataset, which describes the minimum daily temperatures over ten years (1981-1990) in Melbourne, Australia. The dataset consists of 3,650 observations.

[Minimum Daily Temperatures Dataset](https://raw.githubusercontent.com/jbrownlee/Datasets/master/daily-min-temperatures.csv)

## Contents

1. **Autocorrelation Function (ACF):** Calculates the similarity between observations at different time lags.

2. **Partial Autocorrelation Function (PACF):** Determines the partial correlation between time periods, removing the effect of intervening observations.

3. **AR (Auto-Regressive) Model:** Models the impact of previous time periods on the current observation.

4. **MA (Moving Average) Model:** Models the impact of unexpected external factors on the current observation.

5. **ARMA (Auto Regressive Moving Average) Model:** Combines elements of AR and MA models to forecast future values.

6. **ARIMA (Auto Regressive Integrated Moving Average) Model:** A combination of ARMA with an integrated factor to make the time series stationary.

7. **Autocorrelation and Partial Autocorrelation Plots:** Visualization techniques heavily used in time series analysis and forecasting.

8. **Durbin-Watson Test:** Tests for autocorrelation in the residuals of a regression analysis.

9. **Ljung–Box Test:** Tests for the absence of serial autocorrelation and randomness in the residuals.

## Usage

1. Download the dataset and place it in your current working directory with the filename `daily-minimum-temperatures.csv`.

2. Run the provided Python scripts for autocorrelation and partial autocorrelation analysis.

## Acknowledgments

The content of this readme file is based on the provided text and explanations. Special thanks to the contributors and resources mentioned in the text for providing valuable insights into time series analysis and forecasting techniques.
