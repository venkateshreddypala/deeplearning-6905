## Classification of Cats and Dogs using CNN





## Prediction of Stocks for Amazon and Google Using RNN
The First step in order to get the time series data for these stocks is done through the Alpha Vantage which provides an API on registring

I have done this on Mac OS, by using this on my terminal I got an CSV for Amazon

curl -o daily_amzn1.csv "https://www.alphavantage.co/query? function=TIME_SERIES_DAILY&symbol=amzn&apikey=< # Your  API KEY #>&datatype=csv&outputsize=full"

