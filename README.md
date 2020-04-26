<b> Time-Series-Analysis </b>

1.) Time Series Analysis Project with Initially with S&P 500 data. 

2.) Time Series Analysis of USD-GBP exchange rates.

The Data used for fitting the model can be last 180 days or 1 year which is scraped from a website to get live data to get accurate predictions. 

Various smoothing methods are applied like Log transformation, Differencing, Exponential Smoothing etc to make the Time Series stationary before applying an traditional TSA model like ARIMA.

Auto ARIMA can be used to get the optimal parameters for ARIMA after smoothing.

Later RNN and LSTM models are used to get more accurate predictions.

RNN model used first is 1-Hidden layer with 1 neuron and later changed to 2 Hidden Layers with 50 neurons each and ReLU activation function.

LSTM model is used after that.

