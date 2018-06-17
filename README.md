## Classification of Cats and Dogs using CNN

[CNN Readme](https://github.com/venkateshreddypala/deeplearning-6905/tree/master/CNN)



## Prediction of Stocks for Amazon and Google Using RNN

### Datasets for Amazon and Google stocks
The dataset that has been pregenerated and is not most recent.
To get the most recent datasets for the RNN program, you will need to get an API key.

#### Instructions for getting an API key
1. Head to https://www.alphavantage.co/ and click on "GET YOUR FREE API KEY TODAY"
2. Enter in your information then click "GET FREE API KEY"

#### Terminal commands to receive most recent datasets
Now in order to use this key to get the most reccent datasets, you will need to enter it into the terminal
command given below for both the goog dataset and the amzn dataset.


```
curl -o daily_amzn.csv "https://www.alphavantage.co/query? function=TIME_SERIES_DAILY&symbol=amzn&apikey=<APIKEYHERE>&datatype=csv&outputsize=full"

curl -o daily_goog.csv "https://www.alphavantage.co/query? function=TIME_SERIES_DAILY&symbol=amzn&apikey=<APIKEYHERE>&datatype=csv&outputsize=full"
```

We got the following data on the CSV timestamp, open, high, low close, volume, of which I seperated the low close.

For the RNN part we used two popular libraries Tensor Flow and Keras :
1. https://github.com/venkateshreddypala/deeplearning-6905/blob/master/RNN%20Notebook.ipynb
2. https://github.com/venkateshreddypala/deeplearning-6905/blob/master/RNN_Keras.ipynb
