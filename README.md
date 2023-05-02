# bitcoin-forecast
Aim: Training 2 traditional machine learning models, ARIMA and decision tree, and a deep learning model, LSTM(long-Short Term Memory) to forecasting bitcoin price.

The dataset of bitcoin price is scrapped from historical data of financial yahoo: https://finance.yahoo.com/quote/BTC-USD/history?p=BTC-USD, and combined with gold and security prices in the same period.

Result:
- ARIMA: 
    MSE:  3.051770422547035e-05
    R2:  0.9910972029176749
    MAPE:  0.004427980791083941
    RMSE:  0.0055242831413198175
- Decision Tree:
    MSE: 0.0004725653950273249
    RMSE: 0.021738569295777607
    R-squared: 0.8617707512918285
    MPE: 1.82645510976099
    MAPE: 0.0182645510976099
- LSTM:
    MSE: 0.00016963236986879888
    RMSE: 0.01302429920835662
    MAPE: 0.011051499319503659
    R-Squared: 0.9507948613196113
