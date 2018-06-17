## Classification of Cats and Dogs using CNN





## Prediction of Stocks for Amazon and Google Using RNN

### Datasets for Amazon and Google stocks
The dataset that has been pregenerated and is not most recent.
To get the most recent datasets for the RNN program, you will need to get an API key.

#### Instructions for getting an API key
1. Head to https://www.alphavantage.co/ and click on "GET YOUR FREE API KEY TODAY"
2. Enter in your information then click "GET FREE API KEY"

Now in order to use this key to get the most reccent datasets, you will need to enter it into the terminal
command given below for both the goog dataset and the amzn dataset.


'''
curl -o daily_amzn.csv "https://www.alphavantage.co/query? function=TIME_SERIES_DAILY&symbol=amzn&apikey=<APIKEYHERE>&datatype=csv&outputsize=full"

curl -o daily_goog.csv "https://www.alphavantage.co/query? function=TIME_SERIES_DAILY&symbol=amzn&apikey=<APIKEYHERE>&datatype=csv&outputsize=full"
'''

