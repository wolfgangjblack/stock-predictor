## Algo Understanding

1. How does the Prophet Algorithm differ from an LSTM?

- LSTM predictions are based on a set of last values, and therefor are less prone to variance due to seasonality. They used their long short term memory (information from future and past) to consider the current trend. In contrast, the prophet model is an additive system that is sensitive to seasonalities. 

2. Why does an LSTM have poor performance against ARIMA and Profit for Time Series?

- LSTM tends to overfit and needs much larger datasets to outperform ARIMA and Prophet

## Interview Readiness

1. What is exponential smoothing and why is it used in Time Series Forcasting?

- Exponential smoothing is a time series forcasting method that uses an exponentially decreasing weight for past samples. In general smoothing is used to eliminate either fine local variations or large time series variations in data to get a more representative dataset. 

2. What is stationarity?

- a flat looking data series without tred, constance variance over time, a constant autocorrelation structure over time, and no periodic fluctuations.

3. What is seasonality?

- a characteristic of a time series in which the data experiences regular and predictable changes that recur every calendar year

4. Why Is Stationarity Important in Time Series Forecasting?

- Stationarity means that the statistical properties of a time series (or rather the process generating it) do not change over time. Stationarity is important because many useful analytical tools and statistical tests and models rely on it

