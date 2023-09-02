
# Time Series Forecasting for Gas, Electricity, and Water Consumption Data

## Objective

The objective of this project is to utilize Time Series analysis techniques from Statsmodels to forecast Gas, Electricity, and Water Consumption Data. Accurate forecasting of consumption data is crucial for government planning, as it enables them to prepare for potential surges in demand.

## Background Information

The dataset used in this project contains monthly consumption data for gas, electricity, and water. By applying time series forecasting methods, we aim to provide valuable insights and predictions for government decision-makers.

## Code Overview

### Libraries

- **Pandas and NumPy:** Used for data manipulation and analysis.
- **Seaborn and Matplotlib:** Used for data visualization.
- **Statsmodels:** Provides various time series analysis tools.
- **Scikit-learn:** Used for time series split and machine learning metrics.
- **Scipy:** Utilized for statistical functions like Box-Cox transformation.
- **pmdarima:** A library for automatic ARIMA model selection.
- **Warnings:** Used to suppress unnecessary warnings.

### Data Preprocessing

- The dataset is loaded and processed to ensure it is in the appropriate format for time series analysis.

### Exploratory Data Analysis (EDA)

- Visualizations, ADF tests, autocorrelation plots, and partial autocorrelation plots are used to understand the data's characteristics.

### Time Series Forecasting Methods

This project employs several time series forecasting methods, including:

- **Holt-Winters Exponential Smoothing**
- **ARIMA (AutoRegressive Integrated Moving Average) Model**
- **Vector Error Correction Model (VECM)**
- **Noise Reduction By Smoothing**

### Evaluation Metrics

- Mean Absolute Percentage Error (MAPE) is used to assess the accuracy of the forecasts.

## Additional Resources

- [Statsmodels Documentation](https://www.statsmodels.org/stable/index.html)
- [pmdarima Documentation](https://pmdarima.readthedocs.io/en/stable/index.html)

## License

This project is licensed under the MIT License

## References

- *Hyndman, R.J., & Athanasopoulos, G. (2018) Forecasting: principles and practice, 2nd edition, OTexts: Melbourne, Australia. [OTexts.com/fpp2](http://OTexts.com/fpp2). Accessed on 22 July 2023.*

- *G, V.K. (2023) Statistical tests to check stationarity in time series, Analytics Vidhya. Available at: [Analytics Vidhya - Statistical Tests to Check Stationarity in Time Series](https://www.analyticsvidhya.com/blog/2021/06/statistical-tests-to-check-stationarity-in-time-series-part-1/). (Accessed: 22 July 2023).*

- *Brownlee, J. (2020) A gentle introduction to the box-jenkins method for time series forecasting, MachineLearningMastery.com. Available at: [MachineLearningMastery - A Gentle Introduction to the Box-Jenkins Method for Time Series Forecasting](https://machinelearningmastery.com/gentle-introduction-box-jenkins-method-time-series-forecasting/). (Accessed: 28 July 2023).*

- *Rehal, V. (2023) Vector error correction (VECM) and trend specification, SPUR ECONOMICS - Learn and Excel. Available at: [SPUR ECONOMICS - Vector Error Correction (VECM) and Trend Specification](https://spureconomics.com/vector-error-correction-vecm-theory/). (Accessed: 05 August 2023).*
