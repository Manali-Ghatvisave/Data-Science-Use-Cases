
ARIMA and Seasonal ARIMA
Autoregressive Integrated Moving Averages
The general process for ARIMA models is the following:

1 Visualize the Time Series Data
2 Make the time series data stationary
3 Plot the Correlation and AutoCorrelation Charts
4 Construct the ARIMA Model or Seasonal ARIMA based on the data
5 Use the model to make predictions


Autocorrelation and Partial Autocorrelation
Identification of an AR model is often best done with the PACF
For an AR model, the theoretical PACF “shuts off” past the order of the model.The phrase “shuts off” means that in theory the partial autocorrelations are
equal to 0 beyond that point. Put another way, the number of non-zero partial autocorrelations gives the order of the AR model. By the “order of the
model” we mean the most extreme lag of x that is used as a predictor.

Identification of an MA model is often best done with the ACF rather than the PACF.
For an MA model, the theoretical PACF does not shut off, but instead tapers toward 0 in some manner. A clearer pattern for an MA model is in the ACF.
The ACF will have non-zero autocorrelations only at lags involved in the model.

p,d,q p AR model lags d differencing q MA lags