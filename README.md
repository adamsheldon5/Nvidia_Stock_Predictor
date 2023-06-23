# Nvidia_Stock_Predictor
Applying LSTM neural networks for predicting future NVIDIA stock prices

This repository contains a project that aims to predict the future stock prices of NVIDIA corporation using a type of recurrent neural network called Long Short-Term Memory (LSTM).

# Project Description
The project is developed in Python using Keras and scikit-learn libraries. It uses LSTM, a type of recurrent neural network that is capable of learning long-term dependencies, which makes it perfect for the task of stock price prediction.

The LSTM model is trained on the historical daily stock prices of NVIDIA for the period from 2018 to 2022. The model is then used to predict the closing stock prices for the year 2023.

# The stock price data includes:

Date: The day of the recorded price.
Open: The stock price at the beginning of that trading day.
High: The highest price reached during that trading day.
Low: The lowest price reached during that trading day.
Close: The stock price at the end of that trading day.
Volume: The number of shares traded during that trading day.
The data is split into a training set (first 80% of the data) and a test set (last 20% of the data).

# Results
The model's performance is evaluated by plotting the predicted stock prices against the actual prices for the year 2023. The model's predictions show a promising alignment with the actual stock price trend. However, it's important to note that stock price predictions are extremely challenging due to the complexity and volatility of the stock market, and should be used with caution.

The details of the model's architecture, training process, and evaluation are included in the Jupyter notebook.

Important: Please note this is just a project for learning purposes and should not be used to make investment decisions. 

Project was inspired by this fantastic video: https://www.youtube.com/watch?v=OXwZtlcTiuk 

