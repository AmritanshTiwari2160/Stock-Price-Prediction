# 📈 Stock Price Prediction using LSTM, Prophet, and ETS Models

This project explores **stock price prediction** using three distinct time-series forecasting models: **Long Short-Term Memory (LSTM)**, **Prophet**, and **Exponential Smoothing (ETS)**. The dataset comprises **Tesla stock price data** (`TSLA.csv`), and the goal is to analyze and forecast future stock prices using cutting-edge techniques, ultimately evaluating model performance through key metrics like **RMSE** and **MAE**.

## 🗂️ Project Overview

Stock price prediction remains one of the most challenging tasks in financial markets. This project investigates the strengths and limitations of different forecasting models, blending **deep learning**, **additive models**, and **statistical methods** to generate accurate predictions. 

**Three Models Explored:**

1. **LSTM (Long Short-Term Memory):**  
   LSTM is a type of recurrent neural network (RNN) designed to capture long-term dependencies in stock price trends. It excels at time-series forecasting by retaining past information over extended periods, allowing it to predict future movements more accurately.
   
2. **Prophet:**  
   Developed by Facebook, Prophet is an additive model known for its ability to fit non-linear trends, seasonality, and holiday effects. It's robust to missing data and outliers and offers an intuitive interface for handling time-series data.
   
3. **ETS (Exponential Smoothing):**  
   A classical statistical approach, ETS uses weighted averages of past observations to forecast future values. By capturing the **level**, **trend**, and **seasonality**, it smooths out short-term fluctuations, offering reliable predictions.

## 🧑‍💻 Data Preprocessing

To ensure accurate model performance, the raw Tesla stock data is preprocessed with the following steps:

- **Handling missing values**: Missing entries are imputed or removed as necessary.
- **Feature scaling**: Features like opening price, closing price, high, low, and volume are scaled for consistent model training.
- **Training and test splits**: Data is divided into training and testing sets, preserving the sequential nature of stock price time-series data.

## ⚙️ Models in Action

Each model is trained on historical stock data and then used to predict future stock prices. Here's how each approach tackles the challenge:

- **LSTM**: Captures complex patterns in the stock price by modeling long-term dependencies in the time-series.
- **Prophet**: Handles seasonal trends, holidays, and non-linear data variations with ease.
- **ETS**: Focuses on smoothing past observations to predict future prices with trend and seasonality decomposition.

## 📊 Performance Evaluation

Model performance is assessed using the following metrics:

- **Root Mean Squared Error (RMSE)**: Measures the square root of the average squared differences between predicted and actual stock prices.
- **Mean Absolute Error (MAE)**: Calculates the average magnitude of errors between predictions and true values.

### Results:

The comparative analysis of LSTM, Prophet, and ETS reveals each model’s strengths:

- **LSTM**: Best for capturing complex, long-term dependencies in volatile stock data.
- **Prophet**: Ideal for data with strong seasonal trends or recurring patterns.
- **ETS**: Works well with smoother time-series data and captures trend and seasonality efficiently.

## 🔥 Key Takeaways

This project offers a comprehensive exploration of stock price forecasting, comparing **deep learning**, **additive models**, and **statistical methods**. By evaluating each model's strengths and weaknesses, we gain insights into which method is best suited for financial time-series forecasting.

---

### 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stock-price-prediction.git
