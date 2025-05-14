🪙 Cryptocurrency Price Movement Prediction using LSTM
This project predicts the price movement direction (up or down) of a cryptocurrency (e.g., Bitcoin) using historical data and technical indicators, powered by a Long Short-Term Memory (LSTM) neural network.

📌 Features
✅ Historical OHLCV data fetched using yfinance

📉 Technical indicators: SMA, EMA, RSI

📊 Sequence generation for LSTM input

🧠 LSTM deep learning model for binary classification

📈 Performance evaluation (accuracy, charts)

🛠 Technologies Used
Python

Pandas, NumPy, Matplotlib, Seaborn

scikit-learn

TensorFlow / Keras

yfinance for market data

🚀 How It Works
Load Data
Historical price data for BTC-USD is downloaded using Yahoo Finance.

Feature Engineering
Technical indicators like SMA, EMA, and RSI are added to the dataset.

Data Preparation
Time-series sequences are created (e.g., using 60-day windows), and data is normalized.

Model Training
A sequential LSTM model is trained to predict whether the next closing price will be higher (1) or lower (0) than the current one.

Evaluation
The model's accuracy is tracked and visualized using training/validation accuracy plots.

# 1. Clone the repo
git clone this repository

cd crypto-price-prediction

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the notebook
jupyter notebook crypto_predictor.ipynb
