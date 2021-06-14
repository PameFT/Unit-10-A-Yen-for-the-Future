# Unit 10—A Yen for the Future

![Yen Photo](Images/unit-10-readme-photo.png)

## Background

The financial departments of large companies often deal with foreign currency transactions while doing international business. As a result, they are always looking for anything that can help them better understand the future direction and risk of various currencies. Hedge funds, too, are keenly interested in anything that will give them a consistent edge in predicting currency movements.

In this assignment, you will test the many time-series tools that you have learned in order to predict future movements in the value of the Japanese yen versus the U.S. dollar.




- - -

## Analysis

#### 1. Time-Series Forecasting:

In this notebook, I have loaded the historical Dollar-Yen exchange rate futures data and applied the time series analysis and modeling to determine whether there is any predictable behavior.

As a result of these analysis, I have determined the following questions:

1. Based on your time series analysis, would you buy the yen now?

I would not buy Yen, as given the 5-Day Returns Forecast, indicates that the forecast of Yen will decline in the next 5 days.

2. Is the risk of the yen expected to increase or decrease?

The risk of the Yen is expected to increase in the next 5 days, as shown in the 5-Day Volatility Forecast.

3. Based on the model evaluation, would you feel confident in using these models for trading?

These models are really good tools to expand more the fundametal analysis for trading, but I would prefer combine them with other evaluation models to optimise my trading strategy.



#### 2. Linear Regression Forecasting:

In this notebook, I have built a Scikit-Learn linear regression model to predict Yen futures ("settle") returns with *lagged* Yen futures returns and categorical calendar seasonal effects.

I have followed the steps outlined in the regression_analysis starter notebook and completed the following:

1. Data Preparation.
2. Fitting a Linear Regression Model.
3. Making predictions using the testing data.
4. Out-of-sample performance.
5. In-sample performance.

As a result of the linear regression analysis and modeling, I was able to answer the following question:

* Does this model perform better or worse on out-of-sample data compared to in-sample data?

The out-of-sample RMSE is lower than the in-sample RMSE. Therefore, it has better performance.

