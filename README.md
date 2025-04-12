FUTURE_ML_02
Forecasting future stock prices using LSTM-based deep learning models. 
Historical data from Yahoo Finance, evaluated with RMSE, and visualized predicted vs.
actual stock prices using Python, Keras, and Matplotlib.

Stock Price Prediction Using LSTM

A time series forecasting project to predict future stock prices using deep learning models.

Skills Gained
Time Series Analysis
Deep Learning (LSTM)
Data Preprocessing FUTURE_ML_02 — Stock Price Prediction Using LSTM
🔍 Project Overview
A time series forecasting project focused on predicting future stock prices using deep learning models, specifically LSTM (Long Short-Term Memory) neural networks. Historical data was sourced from Yahoo Finance, and model performance was evaluated using RMSE. Results were visualized by comparing predicted vs. actual stock prices.

🎯 Objective
To forecast Apple Inc. (AAPL) stock prices using historical market data and an LSTM-based deep learning model.

🧠 Skills Gained
Time Series Analysis

Deep Learning (LSTM Networks)

Data Preprocessing & Feature Scaling

Regression Evaluation Metrics (RMSE)

Data Visualization with Matplotlib & Seaborn

🧰 Tools & Libraries Used
Programming Language: Python

Data Handling: Pandas, NumPy

Modeling & Preprocessing: Scikit-learn, Keras (TensorFlow backend)

Visualization: Matplotlib, Seaborn

Data Source: Yahoo Finance API via yfinance

📦 Dataset
Source: Yahoo Finance

Stock Ticker: Apple Inc. (AAPL)

Time Range: January 2015 – December 2023

Feature Used: Closing Price

🏗️ Model Architecture
LSTM Layer with 50 units (return sequences=True)

LSTM Layer with 50 units

Dense Output Layer with 1 neuron

Optimizer: Adam

Loss Function: Mean Squared Error (MSE)

📊 Model Evaluation
Metric Used: Root Mean Squared Error (RMSE)

RMSE Achieved: ~5.97

Output: A line plot comparing actual vs. predicted stock prices for the test data.

📉 Additional Analysis
Compared long-term stock trends of Apple (AAPL) and Microsoft (MSFT) using historical closing prices to analyze relative performance.


Regression & Evaluation Metrics (RMSE)
Data Visualization using Matplotlib & Seaborn
Tools & Libraries Used
Python
Pandas
NumPy
Scikit-learn
Keras (TensorFlow backend)
Matplotlib / Seaborn
Yahoo Finance API (via yfinance)
Dataset
The dataset was retrieved using the Yahoo Finance API using the yfinance Python library.
We selected stock data for Apple Inc. (AAPL) from 2015 to 2023.

Model Architecture
LSTM Layer (50 units) → return sequences
LSTM Layer (50 units)
Dense Output Layer (1 neuron)
Optimizer: Adam
Loss Function: Mean Squared Error
Model Evaluation
We used Root Mean Squared Error (RMSE) to evaluate our model's performance.
A comparison of actual vs. predicted stock prices is also visualized.

