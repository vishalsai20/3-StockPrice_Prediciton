# 3-StockPrice_Prediciton


In this project, the aim is to predict future stock prices

For this project I have chosen the stock prices of 'GOOGLE' from 2008 to 2018. 

I had collected the data from Yahoo Finance using the yfinance library in python. The dataset consists of 2518 rows and 6 columns.

Here, I mainly concentrated only on the Closing Prices, and predicted the closing prices.

Initially after loading the dataset, I had performed some basic analysis, then normalized the data in the MinMax Scaling fashion.

Thereafter I had made the training and testing datasets, built the LSTM(Long Short Term Memory) model.

After training the training dataset, I had predicted the testing datapoints using the same model.

My model has produced a R2_score of 0.997 and 0.987 on training set and testing set respectively.

The entire project is clearly demostrated in the notebook.


Further I will be extending this project by prediciting all other features of the stock price and this will help in making patterns of the entire predicted stock price which would be even more astonishing!
