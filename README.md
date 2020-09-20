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

<b>STEP 1</b>
Scraped Wiki's NIFTY50 page to get ticker symbols
Used Quandl API to fetch stock data for past 5 years

<b>STEP 2</b>

Label training data as 0(sell) and 1(buy)
Scale data using sklearn preprocessing libarary

<b>STEP 3 </b>
Build LSTM model in keras.

<b>Usage:</b>
Run the ipynb file on colab or jupyter notebook.
