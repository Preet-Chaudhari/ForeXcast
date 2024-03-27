# Currency Predictor: ForeXcast

## Motivation
In today's globalized world, currency exchange rates play a crucial role in international trade, investments, tourism, and various other economic activities. Predicting exchange rates accurately can provide valuable insights for businesses, investors, and policymakers to make informed decisions and mitigate risks associated with currency fluctuations.

## Data Collection
I have collected historical foreign exchange rate data from a reliable API source, marketdata.tradermade.com, for various currency pairs. The data includes open, close, high, and low rates for each currency pair over a specified time range.

## Problem Statement
The problem I aim to solve is forecasting exchange rates between two currencies accurately for future dates. This prediction can help stakeholders anticipate currency movements and make timely decisions.

## Solution Approach
Our solution involves applying various machine learning and time series forecasting techniques to predict exchange rates. I have explored three different models:

1. **Decision Tree Regressor**: This model learns the relationship between the features (open, high, low rates) and the target variable (closing rate) to make predictions.

2. **MLP (Multilayer Perceptron) Neural Network**: MLP is a type of feedforward artificial neural network that uses multiple layers to learn complex patterns in the data.

3. **Prophet**: Prophet is an open-source forecasting tool developed by Facebook that is well-suited for time series data. It models the trend and seasonality in the data and provides forecasts with uncertainty intervals.

## Data Analysis
We conducted exploratory data analysis to understand the patterns and relationships in the historical exchange rate data. Visualization techniques such as line plots and correlation matrices helped us gain insights into the data.

## Results
- Decision Tree Regressor and MLP models provided reasonable predictions based on the historical data, but Prophet outperformed them in forecasting accuracy.
- Prophet's ability to capture trend changes and seasonality in the data allowed for more accurate predictions of future exchange rates.
- By incorporating additional features such as open, high, and low rates as regressors, we further improved the forecasting accuracy of the Prophet model.

## Conclusion
Our project demonstrates the effectiveness of machine learning and time series forecasting techniques in predicting currency exchange rates. Accurate exchange rate forecasts can empower businesses, investors, and policymakers to make better decisions and mitigate risks associated with currency fluctuations.

## References
- EarnForex: https://www.earnforex.com/guides/high-low-vs-open-close/
- Decision Tree Regression: https://towardsdatascience.com/machine-learning-basics-decision-tree-regression-1d73ea003fda
- Multilayer Perceptron: https://www.sciencedirect.com/topics/computer-science/multilayer-perceptron
- Prophet Documentation: https://facebook.github.io/prophet/

## Done
We have successfully developed a currency predictor system, ForeXcast, which provides accurate forecasts of exchange rates for various currency pairs. This tool can be invaluable for businesses, investors, and policymakers seeking to navigate the complexities of the global financial markets.