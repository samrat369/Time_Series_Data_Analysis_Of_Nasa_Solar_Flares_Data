# CSI2 — Time Series Forecasting of Daily Minimum Temperatures

This project demonstrates **time series forecasting** using **Conv1D + LSTM neural networks** in TensorFlow/Keras.  
It predicts daily minimum temperatures from the **Daily Minimum Temperatures dataset** provided by [Jason Brownlee’s Dataset Repository](https://raw.githubusercontent.com/jbrownlee/Datasets/master/daily-min-temperatures.csv).

---

## 📌 Features
- Downloads and processes historical temperature data
- Prepares time series datasets with **windowed sampling**
- Builds a **hybrid CNN-LSTM model** for sequence prediction
- Uses **EarlyStopping** for better generalization
- Visualizes predictions vs. actual values
- Evaluates model performance with **Mean Absolute Error (MAE)**

---

## 🛠 Tech Stack
- **Python 3.x**
- **TensorFlow / Keras**
- **NumPy & Pandas**
- **Matplotlib**
- **CSV Data Handling**

