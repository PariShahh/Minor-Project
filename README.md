# 📈 Stock Price Prediction

A machine learning project to predict stock closing prices using historical market data. Built during my internship at **Corizo**, this project explores time-series forecasting with classical ML and deep learning approaches.

---

## 📌 Project Summary

Stock price prediction is a classic time-series problem with real-world financial relevance. This project walks through the full ML pipeline — data cleaning, feature engineering, model training, and evaluation — using historical OHLCV (Open, High, Low, Close, Volume) stock data.

---

## 📂 Dataset

| Field | Details |
|---|---|
| **Source** | Historical stock market data (Corizo internship dataset) |
| **Period** | 2018 |
| **Features** | `Date`, `Open`, `High`, `Low`, `Close`, `Volume` |
| **Target** | `Close` price |

---

## 🧪 Models Tried

| Model | Notes |
|---|---|
| Linear Regression | Baseline model |
| Random Forest Regressor | Handles non-linearity, feature importance |
| LSTM (Long Short-Term Memory) | Deep learning for sequential/time-series data |

> Models were evaluated on a held-out test set (80/20 split).

---

## 📊 Evaluation Metrics

| Model | RMSE | R² Score |
|---|---|---|
| Linear Regression | — | — |
| Random Forest | — | — |
| LSTM | — | — |

> ⚠️ *Fill in your actual metric values here after running the notebook.*

---

## 🛠️ Tech Stack

- **Language:** Python 3.x
- **Libraries:** `pandas`, `numpy`, `scikit-learn`, `tensorflow` / `keras`, `matplotlib`, `seaborn`

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/stock-price-prediction.git
cd stock-price-prediction
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch the notebook
```bash
jupyter notebook stock_price_prediction.ipynb
```

---

## 🔄 Live Data Upgrade *(In Progress)*

Currently migrating from static 2018 CSV data to **live stock prices** using the `yfinance` API. This will allow the model to run on any ticker in real time.

```python
import yfinance as yf
df = yf.download("RELIANCE.NS", start="2020-01-01", end="2024-12-31")
```

---

## 📁 Repository Structure

```
stock-price-prediction/
│
├── stock_price_prediction.ipynb   # Main notebook
├── data/
│   └── stock_data.csv             # Historical dataset
├── requirements.txt               # Python dependencies
└── README.md
```

---

## 👩‍💻 Author

**Pari Shah** — Data Scientist  
📍 Mumbai | AudvikLabs  
🔗 [LinkedIn](https://linkedin.com/in/YOUR_PROFILE) · [GitHub](https://github.com/YOUR_USERNAME)

---

## 📝 Acknowledgements

- Internship project completed at **Corizo**
- Dataset sourced during internship programme
