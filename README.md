# Time Series Analysis
This repository consist of 2 time series projects. We tried to forecast stock price and world temperature

## Stock Price Forecasting
We use SARIMAX to forecast stock price and we visualize it the result:

![Screen Shot 2022-08-23 at 00 12 41](https://user-images.githubusercontent.com/106853320/185980862-eead7da5-1d05-47a8-8a42-fe4cb09024c7.png)

Unfortunately we can't predict future VWAP pirce without additional Exog rows, we need future Exog to do this, but overall the train and test result is pretty good.

## World Temperature Forecasting
We use SARIMA to forecast world  and we visualize it the result:

![Screen Shot 2022-08-23 at 00 25 11](https://user-images.githubusercontent.com/106853320/185982393-f3160e1c-0d8b-4b04-8dbf-bfef4a8940ef.png)

The train model looks quite good, then we tried to forecast 2 years ahead and resulted :

![Screen Shot 2022-08-23 at 00 23 48](https://user-images.githubusercontent.com/106853320/185983084-83557e68-4b8c-4875-863d-d310ab0dba1d.png)

