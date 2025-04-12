Hybrid Deep Learning Model for Stock Price Forecasting | Adani Ports

This project implements a hybrid deep learning architecture (CNN-LSTM-GRU) for time series forecasting, inspired by the journal "Time Series Forecasting Based on Deep Learning CNN-LSTM-GRU Model on Stock Prices" (IJETT, 2023).
It utilizes advanced time series concepts including sequence generation, sliding window, normalization, and validation splitting to accurately predict stock prices — specifically tailored for Adani Ports. The model captures both short- and long-term temporal dependencies
and demonstrates enhanced forecasting accuracy through feature extraction and noise reduction.

Link of journal : https://ijettjournal.org/Volume-71/Issue-6/IJETT-V71I6P215.pdf
Link of Dataset :  https://www.kaggle.com/datasets/rohanrao/nifty50-stock-market-data

Journal Summary:
The journal explores the use of a hybrid deep learning model that integrates 1D Convolutional Neural Networks (CNN), Long Short-Term Memory (LSTM), and Gated Recurrent Unit (GRU) architectures to forecast stock prices of Tesla (TSLA), Google (GOOG), and Twitter (TWTR). 
The motivation stems from the limitations of standalone models like LSTM, which struggle with small datasets and capturing complex patterns.

The authors collected five years of historical stock data and used pre-processing techniques, including Min-Max normalization and sliding window approaches, to prepare the data. Two input window sizes (1-day and 30-day) were used to evaluate short- and long-term forecasting capabilities.


Three models were compared:
LSTM
LSTM-GRU hybrid
CNN-LSTM-GRU hybrid

The CNN-LSTM-GRU model consistently outperformed the others in terms of Mean Absolute Error (MAE) and Root Mean Square Error (RMSE), indicating superior accuracy in stock price prediction. CNN effectively extracts features and reduces noise, LSTM captures long-term dependencies, and GRU improves training efficiency.

The study concludes that the CNN-LSTM-GRU hybrid model is highly effective for time series forecasting tasks. Future enhancements could include integrating sentiment analysis from social media or financial news and experimenting with more advanced CNN architectures like AlexNet or GoogleNet.
