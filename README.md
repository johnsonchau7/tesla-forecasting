# Tesla Stock Price Forecasting

<div align="justify">
This project aims to build a univariate time series forecasting model for Tesla stock price in next 24 months from Dec 2020. 
 <br/>
 <br/>
Data is acquired from Yahoo Finance, containing historical stock price of Tesla and this is pre-processed to standardise time format and check for data quality issues. Time series decomposition is done to find useful information on autocorrelation and partial correlation. In the end, ARIMA and Holt Winters model are built and the model with the best cross validation performance is chosen for forecasting. In conclusion, ARIMA model (3,1,3) has the best performance and we can expect Tesla price to raise to $2500 in 2 years time.
 </div>

# References
Source for Tesla stock price data: https://finance.yahoo.com/quote/TSLA/history?p=TSLA
