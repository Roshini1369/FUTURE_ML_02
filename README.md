FUTURE_ML_02
Forecasting future stock prices using LSTM-based deep learning models. Historical data from Yahoo Finance, evaluated with RMSE, and visualized predicted vs. actual stock prices using Python, Keras, and Matplotlib.

Stock Price Prediction Using LSTM

A time series forecasting project to predict future stock prices using deep learning models.

Skills Gained
Time Series Analysis
Deep Learning (LSTM)
Data Preprocessing
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

