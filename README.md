About Dataset
Source: https://www.kaggle.com/datasets/purvitsharma/stock-sentiment

Introduction

Stocks Sentiment dataset contains text, Tweets, related to changes in Stock prices and its other necessary statistics like whether the customer is willing to buy or sell the stocks.

Data Info

There are Two columns in the dataset representing Text and its respective sentiment regarding Stocks.

Models: 

Palonka_LSTM.ipynb: data cleansing, LSTM model, function which predicts sentiment of the sentence

Palonka_GloVe.ipynb: clean data from 'Palonka_LSTM.ipynb', model using GloVe

Palonka_RoBERTa.ipynb: clean data from 'Palonka_LSTM.ipynb', model with fine-tuning RoBERTa, function which predicts sentiment of the sentence

