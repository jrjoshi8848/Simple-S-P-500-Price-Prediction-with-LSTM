# Simple-S-P-500-Price-Prediction-with-LSTM

This simple project is intended to showcase how LSTM model can be used to predict S&P 500 stock price for next day.
This implementation uses past 30 days daily closing price to predictnext daily closing price.
I have used past 1 year daily closing price fetched from Yahoo Finance to train the LSTM models.
The dataset is converted into data frames using pandas. Each frame consists of consecutive 30 days daily closing price which makes aroung 365 frames from one year data.
The implementation can be found in   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Km08ZdftHuY6Lf8EAgtYlxVOYMDTfxEV?usp=sharing)
