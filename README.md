# README: Predicting Earth Surface Temperature Using Machine Learning

## Overview
This project aims to predict global temperature trends using historical data from **1750 to 2015**. The focus is on utilizing the **ARIMA (Auto Regressive Integrated Moving Average)** model for time series analysis to forecast future temperature changes. The dataset, sourced from **Berkeley Earth**, includes over 1.6 billion temperature reports from various archives. The project investigates the limitations of ARIMA in long-term forecasting and complements it with **linear regression** for more accurate predictions.

## Key Components
- **Dataset**: Monthly global temperature data from 1750 to 2015, retrieved from Berkeley Earth archives.
- **Machine Learning Models**:
  - **ARIMA**: Used for short-term temperature forecasting but exhibited limitations in longer horizons due to cumulative errors.
  - **Linear Regression**: Provided more accurate results, revealing a long-term trend of rising global temperatures.
- **Tools and Libraries**: Python libraries such as `NumPy`, `Pandas`, `TensorFlow` and `Matplotlib` were used for data manipulation and visualization. Machine learning methods such as Convolutional Neural Network (CNN) and decision tree are used to capture patterns

## Results
- The ARIMA model produced forecasts with minor discrepancies when compared to real-world data. The highest temperatures in the forecast showed a declining trend, inconsistent with current climate change trends.
- **Linear regression analysis** revealed a positive coefficient, indicating a long-term warming trend consistent with the reality of global warming.

## Conclusion
The ARIMA model is effective for short-term forecasting but has limitations when used for long-term predictions due to external factors like policy changes or sudden climatic events. The addition of **linear regression** improved accuracy and reflected the current trends of rising temperatures. Future work should include scenarios based on varying emission rates to better anticipate potential climate changes.

## Recommendations
Further improvements could involve using hypothetical emission scenarios to better model future climate conditions. These scenarios would allow the system to account for a wider range of potential outcomes, helping to inform climate-related decision-making.
