# Imbalanced Data Handling Techniques

## Introduction
In time series, dealing with imbalanced datasets is a common challenge. Imbalanced datasets refer to datasets where the distribution of classes is skewed, with one class (the majority class) significantly outnumbering the other class(es) (the minority class(es)). This README provides an overview of two techniques commonly used to address this issue: upsampling and downsampling.

## License
This repository is licensed under the BSD-2-Clause License. See the [LICENSE](LICENSE) file for details.

## Upsampling and Downsampling

### What is Upsampling and Downsampling?
- **Upsampling:** Upsampling involves increasing the number of samples in the minority class by randomly duplicating observations. This helps to balance the class distribution.
- **Downsampling:** Downsampling entails reducing the number of samples in the majority class by randomly removing observations. This prevents the dominance of the majority class in the dataset.

### Examples of Imbalance
Imbalanced datasets are characterized by varying degrees of class proportions:
1. **Mild:** 20-40% of the dataset comprises the minority class.
2. **Moderate:** 1-20% of the dataset comprises the minority class.
3. **Extreme:** Less than 1% of the dataset comprises the minority class.

### Upsampling Technique
To perform upsampling:
1. Separate observations from each class into different DataFrames.
2. Resample the minority class with replacement to match the number of samples in the majority class.
3. Combine the up-sampled minority class DataFrame with the original majority class DataFrame.

### Downsampling Technique
To perform downsampling:
1. Separate observations from each class into different DataFrames.
2. Resample the majority class without replacement to match the number of samples in the minority class.
3. Combine the down-sampled majority class DataFrame with the original minority class DataFrame.

### Resampling Time Series Data
Resampling is also applicable in time series data analysis:
- **Downsampling:** Reduces the frequency of time series data.
- **Upsampling:** Increases the frequency of time series data.

## Setting Up Your Data
To use these techniques with your dataset:
- Ensure your dataset has a date column that can be parsed by pandas.
- Have at least one variable of interest for analysis (e.g., price, sales, etc).

### Data Setup Example (Nvidia Stock Price Data)
1. Load necessary packages.
2. Set the theme and settings for future plots.
3. Load your dataset into a DataFrame using `pandas.read_csv()`.
4. Check if the index is correctly parsed as a date.

### Downsampling Data
Downsampling involves reducing high-frequency data to a lower frequency, often by aggregating data points. Example: converting daily data to monthly data.

### Upsampling Data
Upsampling entails increasing low-frequency data to a higher frequency. Example: converting daily data to hourly data. Missing data points are filled using techniques like `fillna()`, `ffill()`, or `interpolate()`.

## Conclusion
Balancing imbalanced datasets is crucial for effective machine learning model training. Upsampling and downsampling are useful techniques to address class imbalance, particularly in classification tasks.

Feel free to swap in your dataset following the provided template.

For more details and implementation, refer to the provided code snippets.

**Note:** Ensure proper attribution to original sources and adhere to licensing terms when using code snippets.
