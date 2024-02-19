# Time Series Analysis and Preprocessing

This repository contains Python code for analyzing time series data, specifically focusing on checking stationarity, trend, and seasonality, and removing them from the data to prepare it for forecasting models.

## Table of Contents

1. [Introduction](#introduction)
2. [Stationarity, Trend, and Seasonality](#stationarity-trend-and-seasonality)
3. [Removing Trend and Seasonality](#removing-trend-and-seasonality)
4. [Load Time Series Dataset](#load-time-series-dataset)
5. [Decompose Time Series](#decompose-time-series)
6. [Checking Stationarity](#checking-stationarity)
7. [Removing Trend](#removing-trend)
8. [Removing Seasonality](#removing-seasonality)

## Introduction

Time series data often contains trends and seasonality that can affect forecasting accuracy. This repository provides insights and techniques to analyze and preprocess time series data using Python.

## Stationarity, Trend, and Seasonality

Stationarity is a crucial concept in time series analysis. A stationary time series is one whose statistical properties, such as mean, variance, and autocorrelation, do not change over time.

Trend refers to the long-term movement or direction in the data. It can be upward, downward, or horizontal.

Seasonality represents variations that occur at specific intervals, such as daily, weekly, monthly, or yearly patterns.

## Removing Trend and Seasonality

To make time series data stationary, we need to remove trend and seasonality. Various techniques can be employed for this purpose, including log transformation, power transformation, differencing, and linear regression.

## Load Time Series Dataset

We utilize the Air Passengers dataset, which records the number of US airline passengers from 1949 to 1960 on a monthly basis.

## Decompose Time Series

We decompose the time series data into its trend, seasonality, and residual components using the `seasonal_decompose` function from the `statsmodels` module.

## Checking Stationarity

We check the stationarity of the time series data using rolling mean and the Dickey-Fuller test.

## Removing Trend

We employ various techniques to remove trend from the time series data, such as log transformation, power transformation, and applying moving window functions.

## Removing Seasonality

Finally, we remove seasonality from the data using differencing techniques applied to different transformations of the time series.

## License

This project is licensed under the BSD-2-Clause License.

## Contributors

- [mudit2004](https://github.com/mudit2004)

Please feel free to contribute to this project by submitting pull requests or raising issues. Thank you!
