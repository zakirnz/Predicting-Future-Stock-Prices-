# Predicting Future Stock Prices

This project focused on applying deep learning models (**LSTM, CNN and GRU**) to predict future stock prices using historical stock data from **Apple and Microsoft**. The study aimed to determine which deep learning architecture performs best in capturing **market trends and price fluctuations** while assessing the impact of **feature engineering and technical indicators** on forecasting accuracy.

## Key Contributions & Achievements

### 📌 Data Collection & Preprocessing
- Collected **seven years (2017–2024)** of historical stock price data from **Yahoo! Finance** using `yfinance`.
- Applied **Exploratory Data Analysis (EDA)** to identify **trends, volatility and daily returns**.
- Implemented **MinMax scaling, sequence generation (60-day lookback window) and feature engineering**:
  - **RSI (Relative Strength Index)**
  - **MACD (Moving Average Convergence Divergence)**
  - **Bollinger Bands**
  - **Moving Averages**

### 📌 Deep Learning Model Development
- Built and trained **six models**:
  - **Base models:** LSTM, GRU, CNN.
  - **Feature-engineered models:** LSTM, GRU, CNN with technical indicators.
- Designed **custom architectures** with:
  - **Multiple layers**
  - **Dropout regularisation**
  - **Batch normalisation**
  - **Adaptive learning rate optimisation**

### 📌 Stock Price Forecasting & Comparative Analysis
- Trained models to **predict stock prices for the next 4 days**.
- Evaluated models using:
  - **MAE (Mean Absolute Error)**
  - **MSE (Mean Squared Error)**
  - **RMSE (Root Mean Squared Error)**
- **Key findings:**
  - **LSTM** consistently outperformed **CNN and GRU** in forecasting accuracy.
  - **Feature-engineered models** improved predictive performance by **reducing MAE and RMSE**.
  - **GRU was computationally more efficient** but had slightly lower accuracy than LSTM.
  - **CNN struggled with long-term dependencies** but excelled in **short-term trend detection**.

### 📌 Business & Financial Implications
- **Highlighted the limitations** of deep learning models, including:
  - **Sensitivity to volatile market conditions**
  - **Computational cost**
  - **Overfitting risks**
- **Proposed future research** into **hybrid models integrating Transformer architectures** (e.g., Attention-based LSTMs) for improved performance.

---
🚀 **This project demonstrates expertise in deep learning, financial time series forecasting and quantitative analysis.**
