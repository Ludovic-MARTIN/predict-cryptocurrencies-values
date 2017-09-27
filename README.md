# predict-cryptocurrencies-values
Predict values of crypto currencies

This project has been run with python 3.6

There are 3 repositories :
- cryptocurrency_urls
this repository contains list of URLs to gather historical crypto currencies data.
- crypto_coins_hist_data
this repository contains all data for each crypto currencyn one file per crypto currency.
- crypto_data
this last repository contains the crypto currencies selected according to the market cap.

1) Webscraping 
The project begins collecting data with the python package : beautifullSoup

2) Data cleaning and crypto coins selection
The data cleaning, formating and coin selection is done thanks to Sqlite

3) The main part
- we explore data with numpy, pandas
- plot some data analyze with seaborn, matplotlib
- create features and generate labels
- and build models with sklearn
