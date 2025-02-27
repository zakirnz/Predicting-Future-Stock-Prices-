# Predicting-Future-Stock-Prices-
This project focused on applying deep learning models (LSTM, CNN and GRU) to predict future stock prices using historical stock data from Apple and Microsoft. The study aimed to determine which deep learning architecture performs best in capturing market trends and price fluctuations while assessing the impact of feature engineering and technical indicators on forecasting accuracy.
Key Contributions & Achievements:
•	Data Collection & Preprocessing:
o	Collected seven years (2017–2024) of historical stock price data from Yahoo! Finance using yfinance.
o	Applied Exploratory Data Analysis (EDA) to identify trends, volatility, and daily returns.
o	Implemented MinMax scaling, sequence generation (60-day lookback window) and feature engineering (RSI, MACD, Bollinger Bands and Moving Averages) to enhance model performance.
•	Deep Learning Model Development:
o	Built and trained six models:
	Base models: LSTM, GRU, CNN.
	Feature-engineered models: LSTM, GRU, CNN with technical indicators.
o	Designed custom architectures with multiple layers, dropout, batch normalization and adaptive learning rate optimisation.
•	Stock Price Forecasting & Comparative Analysis:
o	Trained models to predict stock prices for the next 4 days.
o	Evaluated models using MAE (Mean Absolute Error), MSE (Mean Squared Error) and RMSE (Root Mean Squared Error).
o	Key findings:
	LSTM consistently outperformed CNN and GRU in forecasting accuracy.
	Feature-engineered models improved predictive performance by reducing MAE and RMSE.
	GRU was computationally more efficient but had slightly lower accuracy than LSTM.
	CNN struggled with long-term dependencies but excelled in short-term trend detection.
•	Business & Financial Implications:
o	Highlighted the limitations of deep learning models including sensitivity to volatile market conditions, computational cost and overfitting risks.
o	Proposed future research into hybrid models integrating Transformer architectures (e.g., Attention-based LSTMs) for improved performance.
