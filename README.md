# A Yen For The Future

## Background

The financial departments of large companies often deal with foreign currency transactions while doing international business. As a result, they are always looking for anything that can help them better understand the future direction and risk of various currencies. Hedge funds, too, are keenly interested in anything that will give them a consistent edge in predicting currency movements.
In this Analysis, I will test my data using the ARMA, ARIMA, and GARCH models in order to predict future movements in the value of the Japanese yen versus the U.S. dollar.

## Time-Series Forecasting

### The Following has been utilized in analysing historical data for the Yen:

Time Series Forecasting
Linear Regression Modeling

## Questions to be answered

1. Based on your time series analysis, would you buy the yen now?
2. Is the risk of the yen expected to increase or decrease?
3. Based on the model evaluation, would you feel confident in using these models for trading?

## Steps Taken:

1. Decomposition using a Hodrick-Prescott Filter (Decompose the Settle price into trend and noise).
2. Forecasting Returns using an ARMA Model.
3. Forecasting the Settle Price using an ARIMA Model.
4. Forecasting Volatility with GARCH.

## Conclusion

![Test Image 1](https://github.com/natyrrr/A_Yen_For_The_Future/blob/master/Screen%20Shot%202020-08-27%20at%2010.07.20%20PM.png)

![Test Image 2](https://github.com/natyrrr/A_Yen_For_The_Future/blob/master/ARIMA.png)

![Test Image 3](https://github.com/natyrrr/A_Yen_For_The_Future/blob/master/SETTLE%20VS.%20TREND.png)

![Test Image 4](https://github.com/natyrrr/A_Yen_For_The_Future/blob/master/5%20days%20return.png)

![Test Image 5](https://github.com/natyrrr/A_Yen_For_The_Future/blob/master/GARCH.png)

![Test Image 6](https://github.com/natyrrr/A_Yen_For_The_Future/blob/master/Volatility.png)

Based on the time series analysis, I would not feel confident buying Yen because both the ARIMA model and the ARMA model have a P > 0.05. Therefore they are not significant. However, the GARCH model is significant predicting volatility.This is important when trading derivitives because as per this model it states the volatility will keep increasing in the next 5 days, therefore trading derivitives would be your best option.The GARCH model is also useful to quantify you're maximum loss as you can calculate what you're risk is in purchasing Yen.

I would not feel comfortable using these models to trade. ARMA and ARIMA are not accurate and the other is only slightly useful in a specific kind of investing.

## Linear Regression Forecasting

### Does this model perform better or worse on out-of-sample data compared to in-sample data?

### Steps taken:

1. Data Preparation (Creating Returns and Lagged Returns and splitting the data into training and testing data)
2. Fitting a Linear Regression Model.
3. Making predictions using the testing data.
4. Out-of-sample performance.
5. In-sample performance.

## Conclusion

In this particular model, The out of sample performed slightly better than the In-sample data. The Out-of-sample had a root mean squared error of 0.415, while the in-sample data has an RMSE of .596. From this data I would say the model has a "good" fit. 







