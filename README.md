# Stock Market Analysis & Price Prediction using LSTM 📈🤖

## 📌 Project Overview
This project focuses on **Stock Market Analysis and Price Prediction** using **LSTM (Long Short-Term Memory)**, a deep learning model that works well with **time-series data**.  
The goal is to analyze historical stock prices and predict future closing prices using past trends.

This project demonstrates skills in:
- Time-series forecasting
- Deep Learning (LSTM)
- Data preprocessing & feature scaling
- Model evaluation & visualization

---

## 🎯 Objectives
- Perform exploratory analysis on stock price data
- Preprocess and prepare time-series sequences for LSTM
- Build and train an **LSTM-based prediction model**
- Predict future stock closing prices
- Evaluate prediction accuracy using standard metrics

---

## 🛠️ Tools & Technologies Used
- **Python**
- **Pandas, NumPy**
- **Matplotlib**
- **Scikit-learn**
- **TensorFlow / Keras**
- **Jupyter Notebook / VS Code**

---

## 📂 Dataset
The dataset contains historical stock price data with columns such as:
- Date
- Open
- High
- Low
- Close
- Volume

📌 Data can be collected using:
- Yahoo Finance (`yfinance`)
- Kaggle datasets
- CSV file from stock market sources

---

## 🔍 Workflow / Methodology

### 1️⃣ Data Collection
- Import stock price data using `yfinance` or a CSV file

### 2️⃣ Data Preprocessing
- Handle missing values
- Select the **Close price** for prediction
- Apply **MinMaxScaler** for normalization
- Create time-series sequences (sliding window approach)

### 3️⃣ Model Building (LSTM)
- Input layer → LSTM layer(s) → Dense output layer
- Use optimizer: **Adam**
- Loss function: **Mean Squared Error (MSE)**

### 4️⃣ Model Training
- Train model on historical stock data
- Use validation split to monitor performance

### 5️⃣ Prediction & Evaluation
- Predict stock prices on test dataset
- Compare predicted vs actual closing prices
- Evaluate using:
  - RMSE (Root Mean Squared Error)
  - MAE (Mean Absolute Error)

---

## 📊 Results
The model predicts stock closing prices based on historical patterns.  
Performance can be improved further by tuning hyperparameters and adding more features.

---

## 📌 Future Improvements

- Add more technical indicators (RSI, MACD, Moving Averages)

- Use multi-feature input instead of only Close price

- Try Bidirectional LSTM / GRU

- Deploy using Streamlit

## 👩‍💻 Author

Astik Kumar Jha
Aspiring Data Analyst / ML Developer
