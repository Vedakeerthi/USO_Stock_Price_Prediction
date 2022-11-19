# Time series analysis

## Components of TS
---
1. Trend : Only when the trend is there the graph goes high, else down or horizontal ex 
2. Seasonal : The graph goes high for a particular season ex christmas
3. Irrational : The noise are the graph goes high for a small trend and disappears
4. Cyclic : This graph goes up and down and repeats iteratively

## When not to use TS
---
1. Should not use when the sales are constant.
2. Should not use when the sales follows some function for example, x = sin(x).

## Stationarity
---
TS has a particular behaviour over time, it has a high probability that it will follow the same in the future, this criteria is known as stationarity.
It happens when:
1. Constant mean
2. Constant variance
3. Constant auto covariance

## Test to check stationarity
---
1. Rolling Statistics : Plot the moving average or moving variance and see if it varies.
2. ADCF Test (Augumented Dickey fuller test) : Null hypothesis test is used to find the part whether it is stationary or not.

## What is ARIMA
---
AR I MA = Auto regressive Integrated Moving Average
AR(p) -> Auto regressive lag, finds out the correlation between t and t-3 can be found using PACF (Partial Autocorrelation)
MA(q) -> Moving average is found out can be found using ACF (Autocorrelation)
I(d) -> Order of differentiation can be found using differencing value

## ADFC Test(Augumented Dickey Fuller Test):
---
P value : should always be less than or equal to 0.5
And the critical value should be greater than the test statistics

