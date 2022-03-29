
## Introduction

Stock Price Prediction with LSTM

LSTM stands for Long Short Term Memory Networks. It is a type of recurrent neural network that is commonly used for regression and time series forecasting in machine learning. It can memorize data for long periods, which differentiates LSTM neural networks from other neural networks. 
## Stock Price Prediction with LSTM

Using LSTM is one of the best machine learning approaches for time series forecasting. LSTMs are recurrent neural networks designed to remember data for a longer period. So, whenever you are working on a problem where your neural network fails to memorize data, you can use LSTM neural network.
## Setting up the environment:
yfinance

plotly


##  Preprocessing

A candlestick chart gives a clear picture of the increase and decrease in stock prices, so let’s visualize a candlestick chart of the data before moving further

Now let’s have a look at the correlation of all the columns with the Close column as it is the target column

Training LSTM for Stock Price Prediction

Now I will start with training an LSTM model for predicting stock prices. I will first split the data into training and test sets

Now I will prepare a neural network architecture for LSTM

Now here is how we can train our neural network model for stock price prediction

Now let’s test this model by giving input values according to the features that we have used to train this model and predicting the final result

So this is how we can use LSTM neural network architecture for the task of stock price prediction.


## Summary

LSTM stands for Long Short Term Memory Networks. It is a recurrent neural network designed to remember data for longer. Using LSTM is one of the best machine learning approaches for time series forecasting.