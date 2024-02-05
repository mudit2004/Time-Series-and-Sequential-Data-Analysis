# Time Series Visualization

## Overview
This repository provides code examples and explanations for visualizing time series data using various techniques including line plots, histograms, box plots, heat maps, lag plots, and autocorrelation plots. The goal is to explore the temporal structure and distribution of observations in time series data.

## Requirements
- Python 3.x
- Pandas
- Matplotlib

## Data Set Used
The Minimum Daily Temperatures Dataset describes the minimum daily temperatures over 10 years (1981-1990) in Melbourne, Australia. The dataset contains 3,650 observations in degrees Celsius. You can download the dataset from [here](https://link-to-your-dataset).

## Instructions
1. Download the dataset and place it in the current working directory with the filename “daily-minimum-temperatures.csv”.
2. Run the provided Python scripts to visualize the time series data.

## Contents
### 1. Time Series Line Plot
- Visualizes observations over time using line plots.
- Compares line plots for different intervals (day-to-day, month-to-month, year-to-year).
- Groups data by year and creates a line plot for each year.

### 2. Time Series Histogram and Density Plots
- Explores the distribution of observations using histograms and density plots.
- Provides insights into the underlying distribution of the observations.
- Demonstrates the use of density plots for a smoother summary of the distribution.

### 3. Time Series Box and Whisker Plots by Interval
- Summarizes the distribution of observations by time interval using box and whisker plots.
- Helps identify outliers and trends within each interval.

### 4. Time Series Heat Maps
- Represents observations as a matrix to visualize patterns over time.
- Utilizes heat maps to compare observations between intervals and months.

### 5. Time Series Lag Scatter Plots
- Explores the relationship between observations and their lag values using scatter plots.
- Helps identify positive or negative correlations between observations and lag values.

### 6. Time Series Autocorrelation Plots
- Quantifies the strength and type of relationship between observations and their lags using autocorrelation plots.
- Helps understand how the correlation changes over lag.

## Usage
- Clone the repository.
- Install the required dependencies.
- Run the provided Python scripts to visualize your time series data.

## Contributors
- [Mudit golchha](https://github.com/mudit2004)

## License
This project is licensed under the BSD-2 License. See the [LICENSE](LICENSE) file for details.
