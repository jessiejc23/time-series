# time-series

190317: Completed tutorial
TBC: https://www.kaggle.com/c/demand-forecasting-kernels-only/data

# Notes
Main source: https://machinelearningmastery.com/time-series-forecasting/

**Factors affecting time series forecasting**

a. Long term trend (T^t): overall movement/general direction, ignoring short-term effects

b. Cyclical movements (C^t): relatively long term patterns of oscillations

c. Seasonal variation (S^t): predictable patterns of ups and downs that occur within a single year or repeat year after year.

d. Noise (N^t): random fluctuations/variations due to uncontrolled factors


**ARIMA (Autoregressive Integrated Moving Average)**

AR: evolving variable of interest is regressed on its own lagged (i.e. prior) values

I: data values have been replaced with the difference between their values and the previous values

MA: regression error is a linear combo of error terms - these values occur at the same time and at various times in the past


**(non-seasonal) ARIMA (p,d,q) made up of nonnegative integers**

AR - p: order (number of time lags) of the autoregressive model

I - d: degree of differencing (the number of times the data has had past values subtracted)

MA - q: order of moving average model
