# 💰 Bitcoin Price Predictor

A machine learning project that predicts Bitcoin prices based on historical data and market trends. This tool helps analyze cryptocurrency price movements and estimate future values using statistical and machine learning models.

---

## 🧠 Algorithm / Logic Used
The predictor is built using **time-series forecasting and regression techniques**:
- **Data Preprocessing**: Collecting Bitcoin price data (OHLC – Open, High, Low, Close), cleaning, and normalizing values.
- **Feature Engineering**: Creating lag features, moving averages, and technical indicators (like RSI, MACD).
- **Model Training**: Algorithms commonly used include:
  - **Linear Regression** – baseline model for price prediction.
  - **LSTM (Long Short-Term Memory)** – deep learning model for sequential time-series data.
  - **Random Forest / XGBoost** – for capturing non-linear relationships.
- **Evaluation**: Metrics like RMSE (Root Mean Square Error) and MAE (Mean Absolute Error) are used to measure accuracy.

---

## ⚙️ Installation & Setup
Follow these steps to download and run the project on your system:

1. **Clone the repository**
   ```bash
   git clone https://github.com/anshp73/bitcoin_price_predictor.git
   cd bitcoin_price_predictor
   ```

2. **Create a virtual environment (recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate      # On Windows
   ```

3. **Install required packages**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the predictor**
   ```bash
   python bitcoin_predictor.py
   ```

---

## 📦 Packages Used
The project typically uses:
- **pandas** – for handling time-series data
- **numpy** – for numerical operations
- **scikit-learn** – for regression models and evaluation
- **tensorflow / keras** – for LSTM deep learning models
- **matplotlib / seaborn** – for visualization
- **requests** – for fetching live Bitcoin price data (optional)

---

## 🚀 Usage
- Prepare your dataset (CSV format with Bitcoin historical prices).
- Train the model or load a pre-trained one.
- Input recent Bitcoin price data to get a predicted future value.
- Visualize predictions vs. actual prices with graphs.

---

## 📈 Example
```bash
python bitcoin_predictor.py --input btc_data.csv
```
Output:
```
Predicted Bitcoin Price (next day): $42,350
```

---

## ⚠️ Disclaimer
This project is for **educational purposes only**. Cryptocurrency markets are highly volatile, and predictions should not be used as financial advice.

---

