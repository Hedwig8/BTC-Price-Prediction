# BTC-Price-Prediction
A model that tries to predict through regression the next closing price of Bitcoin (BTC)

### Dataset

The dataset I'm using contains daily-frequent data of date, open, high, low, close and adjusted close BTC price and the BTC volume. 
I tested the close and adjusted close prices and as they were the same in every row, I haven't considered adjusted close column of data.
I also dropped date column as I didn't want the model to be overfitted in the date values.

### Model

I used the data to train the model with regression, a supervised learning method, with the help of Tensorflow and Keras.
I didn't search a lot about the best layers to use on this specific use, but I found that Long Short-Term Memory works pretty fine in the Neural Network.

### Disclaimer

I'm not trying at all to use this as a way to make my way into BTC, as it would be uncertain and dangerous to buy/sell without any idea, experience or strategy regarding any kind of trading, including BTC trading.

As I already warned you, you should not start trading using this model if you are new to the trading world and/or don't know what you are doing.

With that to the side, if you really want to use that to BTC trade, you could establish some strategy and automatise the buy/sell process connecting the model to some broker API

I'm not responsible for any loss you may have using this model.