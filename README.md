# Stock Price Prediction and Sentiment Analysis using LSTM and LLM

- Collected news sentiment data related to the stock Tesla from the AlphaVantage API. It specifies a date range and retrieves news sentiment data.
- Deployed BERT model which takes the processed summary data from API, analyses the sentiment, and categorizes the data as negative, neutral, or positive based on the content.
- Developed Long Short-Term Memory (LSTM) models for high stock price prediction.
- Implemented two LSTM models:
	○	Model 1: Predicted high stock prices based on historical high prices.
	○	Model 2: Enhanced Model 1 by including sentiment data for stock price prediction.
- Evaluated model performance using the root mean squared error (RMSE) metric to assess predictive accuracy and visualized to compare actual and predicted high stock prices.
