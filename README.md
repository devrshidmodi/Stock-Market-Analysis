# Stock-Market-Analysis

This program is written using the Pandas Python in library, which asks the user to type in a list of any individual stock tickers.For example, they might enter “IBM, MSFT, ORCL, CSCO, XOM”.

The stock data for the past 24 months (up to current date), is then downloaded from Yahoo for all listed tickers. The program then loads all those stock price histories into a Pandas DataFrame. The correlations between each of the input tickers against each Index are then calculated. The result that shows which index correlates most strongly with each individual stock and vice versa is then outputted.
