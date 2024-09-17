# Stock-Price-Prediction
Stock price prediction using LSTM, Prophet, and ETS models. Tesla stock data is preprocessed for time-series forecasting. Performance is evaluated using RMSE and MAE, comparing the strengths of deep learning (LSTM), additive (Prophet), and statistical (ETS) models for accurate financial predictions.

This project investigates the prediction of stock prices by leveraging three distinct time-series forecasting techniques: Long Short-Term Memory (LSTM), Prophet, and Exponential Smoothing (ETS). The dataset used for this project consists of Tesla stock price data (TSLA.csv), which is processed and analyzed to build predictive models.

1. Data Preprocessing
The raw stock data is first preprocessed to make it suitable for model input. This includes handling missing values, scaling features, and creating training and testing sets. Key stock features such as opening price, closing price, high, low, and volume are used as inputs for the models. The time-series nature of stock data is preserved to ensure that future predictions are dependent on previous trends.

2. Models Used
LSTM (Long Short-Term Memory): LSTM, a type of recurrent neural network (RNN), is applied to capture long-term dependencies in stock price trends. It is particularly well-suited for time-series forecasting due to its ability to retain past information over longer periods, helping to predict future stock movements.
Prophet: Developed by Facebook, Prophet is an additive model that fits non-linear trends, seasonality, and holidays. It is robust to missing data and outliers and offers a simple interface for time-series forecasting.
ETS (Exponential Smoothing): ETS, a classical statistical model, uses weighted averages of past observations to make future predictions. It smooths out fluctuations and captures the level, trend, and seasonality in the stock data.
3. Performance Evaluation
The performance of each model is evaluated using Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE) on both the training and test datasets. A comparative analysis of the models highlights their strengths and weaknesses in predicting stock prices, offering insights into the most appropriate model for financial forecasting.

This project aims to provide a comprehensive exploration of stock price prediction techniques, blending deep learning, statistical, and additive models to improve forecasting accuracy.
