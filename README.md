
## Introduction

Stock Price Prediction with LSTM

LSTM stands for Long Short Term Memory Networks. It is a type of recurrent neural network that is commonly used for regression and time series forecasting in machine learning. It can memorize data for long periods, which differentiates LSTM neural networks from other neural networks. 
## Stock Price Prediction with LSTM

Using LSTM is one of the best machine learning approaches for time series forecasting. LSTMs are recurrent neural networks designed to remember data for a longer period. So, whenever you are working on a problem where your neural network fails to memorize data, you can use LSTM neural network.
## Setting up the environment:
yfinance

plotly


##  Preprocessing

![1](https://user-images.githubusercontent.com/99526815/160530583-01ddf387-5b59-427b-8973-3b4917ff34b1.PNG)

A candlestick chart gives a clear picture of the increase and decrease in stock prices, so let’s visualize a candlestick chart of the data before moving further

![2](https://user-images.githubusercontent.com/99526815/160530605-4d04c783-3012-497b-bdf0-e873fb6d44c6.PNG)

Now let’s have a look at the correlation of all the columns with the Close column as it is the target column

![5](https://user-images.githubusercontent.com/99526815/160530629-c4e7e51e-376d-4304-a39e-9c82845dde3b.PNG)

Training LSTM for Stock Price Prediction

Now I will start with training an LSTM model for predicting stock prices. I will first split the data into training and test sets

Now I will prepare a neural network architecture for LSTM

![6](https://user-images.githubusercontent.com/99526815/160530803-6537658a-cfb7-4267-a66a-44f5ac734fde.PNG)

Now here is how we can train our neural network model for stock price prediction

Now let’s test this model by giving input values according to the features that we have used to train this model and predicting the final result

So this is how we can use LSTM neural network architecture for the task of stock price prediction.

![4](https://user-images.githubusercontent.com/99526815/160530835-2fe04e78-bbc0-4f63-a4fd-df7240cd2a3c.PNG)

![3](https://user-images.githubusercontent.com/99526815/160530932-fb5d2edb-0d51-4b11-8b48-32ceec44a413.PNG)

## Summary

LSTM stands for Long Short Term Memory Networks. It is a recurrent neural network designed to remember data for longer. Using LSTM is one of the best machine learning approaches for time series forecasting.
