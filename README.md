# Stock-Market-Prediction-using-LSTM
Stock Market Prediction using Deep Learning(LSTM)
Dependencies:
numpy
beautifulsoup4
requests
pandas
tensorflow
keras
sklearn
Overview
Predicting NIFTY50 index movement for 7 days period. LSTM layers are used in keras to predict NIFTY50 index movement for 7 days period.

Project is divided into three parts:

STEP 1
Scraped Wiki's NIFTY50 page to get ticker symbols
Used Quandl API to fetch stock data for past 5 years
STEP 2
Label training data as 0(sell) and 1(buy)
Scale data using sklearn preprocessing libarary
STEP 3
Build LSTM model in keras.
Usage:
Run the ipynb file on colab or jupyter notebook.
