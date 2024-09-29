# Stock Market Forecasting:
Stock market or share market is the aggregation of buyers and sellers of stocks (shares), which represent ownership claims on businesses; these may include securities listed on a public stock exchange, as well as stock that is only traded privately, such as shares of private companies which are sold to investors through equity crowdfunding platforms. Investment in the stock market is most often done via stockbrokerages and electronic trading platforms. Investment is usually made with an investment strategy in mind.

## Problem Statement:
The task of stock prediction has always been a challenging
problem for statistics experts. The main reason
behind this prediction is buying stocks that are likely to
increase in price and then selling stocks that are probably
to fall. Generally, there are two ways for stock market prediction.
-> First:- Fundamental analysis is one of them and relies on a
company's technique and fundamental information like market position, expenses and annual growth rates.
->second:-
Technical analysis method, which concentrates on
previous stock prices and values.

### Approach: ###

We will find the distribution of close and open. Then we will find the correlation between close and open. After that, we will visualize the attributes[Open, High, Low, Close, volume] of our datasets. Then we forecast the stock prices using deep learning concepts like LSTM.

![Alt text](https://github.com/Pritam0018/Stock_Market_Forecasting/blob/main/data/LSTM.png) 

-LSTMs (Long Short-Term Memory networks) are a type of RNNs and provide an advantage in learning from sequence data which makes forecasting stock prices well-suited. Temporal dependencies and patterns in historical price data. Since the prices of the stock market have patterns and changes, if we feed them to LSTM with past and technical indicators values, it can predict to trading times. The trained model can then be used to predict what future stock price depending on those learned patterns.


![Alt text](https://github.com/Pritam0018/Stock_Market_Forecasting/blob/main/data/plot_1.png) 

### Forecasting Part: ###

Stock Prices forecasted for upcoming one month for GOOGLE.

![Alt text]()
