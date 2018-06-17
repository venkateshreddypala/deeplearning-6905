## Classification of Cats and Dogs using CNN





## Prediction of Stocks for Amazon and Google Using RNN
In order to do the RNN I need time series data of the stocks for the date June 9 2018, I have gone to the https://www.alphavantage.co website in order to generate an API from which I could get the data into my system. The API generated is 68VJ3XXXXA5GD6C, using this I have downloaded the data for AMAZON and GOOGLE stocks for the past 45 days and the data is in the directory of the Sorce Code.



The First step in order to get the time series data for these stocks is done through the Alpha Vantage which provides an API on registring

I have done this on Mac OS, by using this on my terminal I got an CSV for Amazon

curl -o daily_amzn1.csv "https://www.alphavantage.co/query? function=TIME_SERIES_DAILY&symbol=amzn&apikey=< # Your  API KEY #>&datatype=csv&outputsize=full"

I got the following data on the CSV timestamp,	open,	high,	low	close,	volume, of which I seperated the low close.

For the RNN part we used two popular libraries Tensor Flow and Keras :

## 1. https://github.com/venkateshreddypala/deeplearning-6905/blob/master/RNN%20Notebook.ipynb
## 2. https://github.com/venkateshreddypala/deeplearning-6905/blob/master/RNN_Keras.ipynb



