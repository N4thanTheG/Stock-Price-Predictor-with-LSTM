# Hello! I'm Nathan and this is my first ever self made project on Github!
This project is a predictive tool that uses an **LSTM neural network** to forecast the **next-day closing price** of any publicly listed stock.

🔍 In addition to prediction, it suggests a simple trading action:
- ✅ **BUY** — if a significant price increase is expected  
- ❌ **SELL** — if a significant drop is expected  
- 🟰 **HOLD** — if the change is minimal

This was also an initial way for me to practice my data analytics as well so I try to keep it simple and easy to understand for everyone!
---

## 💡 Features

- 📅 **Auto-updating**: Always fetches the latest data from Yahoo Finance  
- 🧠 **LSTM model**: Learns from past 60-day sequences  
- 🎛️ **Interactive**: Users can input any stock ticker (e.g. AAPL, TSLA, MSFT)  
- 📊 **Model evaluation**: RMSE and R² included  
- 🖼️ **Clear visuals**: Plots actual vs predicted prices with clear action signals  

---

## 🛠️ Tech Stack
- `yfinance` – For live financial data  
- `TensorFlow / Keras` – LSTM modeling  
- `Scikit-learn` – Scaling + metrics  
- `Matplotlib` – Visualizations  
- `ipywidgets` – User input handling in Jupyter Notebook  

---

## 🚀 Getting Started

### ▶️ Run in Jupyter Notebook:
1. Clone this repository  
2. Open `Stock Closing Price Predictor.ipynb`  
3. Run all cells in sequence  
4. Type in any stock ticker you want to predict!
