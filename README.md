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

![Test Image 1](https://github.com/natyrrr/A_Yen_For_The_Future/blob/master/Screen%20Shot%202020-08-28%20at%201.21.04%20PM.png)

![Test Image 2](https://github.com/natyrrr/A_Yen_For_The_Future/blob/master/Screen%20Shot%202020-08-28%20at%201.26.34%20PM.png)

![Test Image 3](https://github.com/natyrrr/A_Yen_For_The_Future/blob/master/Screen%20Shot%202020-08-28%20at%201.25.16%20PM.png)

![Test Image 4](https://github.com/natyrrr/A_Yen_For_The_Future/blob/master/5%20days%20return.png)

![Test Image 5](https://github.com/natyrrr/A_Yen_For_The_Future/blob/master/GARCH.png)

![Test Image 6](https://github.com/natyrrr/A_Yen_For_The_Future/blob/master/Volatility.png)

1.
2.
3.

## Linear Regression Forecasting

### Does this model perform better or worse on out-of-sample data compared to in-sample data?

### Steps taken:

1. Data Preparation (Creating Returns and Lagged Returns and splitting the data into training and testing data)
2. Fitting a Linear Regression Model.
3. Making predictions using the testing data.
4. Out-of-sample performance.
5. In-sample performance.

## Conclusion








