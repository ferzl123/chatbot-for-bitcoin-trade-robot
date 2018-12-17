

##  Into
A Bitcoin trade robot based on Tensorflow LSTM model.

##  DataSet
The data is got from https://api.btctrade.com/api/trades?coin=btc with requests.It includes 50 trades of Bitcoin.
get_trades.py will get the trades and show you with a picture.


##  Model
rnn_predicter.py uses LSTM model.It use 10 trades as input ,if the next price is bigger than the 10st one ,the result is [1,0,0],if the next price is smaller than the 10st one ,the result is [0,0,1],if the next price is equal as 10st one ,the result is [0,1,0].

So,the [1,0,0] means that the price of Bitcoin will be higher.

##  Result
https://github.com/ferzl123/chatbot-for-bitcoin-trade-robot/master/README.MD

## Update

model saver

data saver
