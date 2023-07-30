# TESLA-Future-Stock-Price-Prediction
Tesla’s stock price is predicted over some months using an LSTM (Long Short-Term Memory) model. Tweets about Tesla are used to improve prediction accuracy.

First, the stock price is predicted over some months using an LSTM Multivariate Time-Series Prediction model. Then, tweets about Tesla are cleaned and their daily average sentiment scores are computed using TextBlob. Lastly, the daily average sentiment scores are added as a feature in the LSTM model and used for prediction.

Disclaimer: The LSTM model cannot be used to predict stock prices in real life because the stock market is highly unpredictable. Prediction models do not work. In this project, the validation phase is used to test the model's performance. The purpose of the project is to implement Multivariate Time-Series Prediction using LSTM.
