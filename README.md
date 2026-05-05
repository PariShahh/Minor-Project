# 📈 Stock Price Prediction — Reliance Industries (NSE)

A machine learning project to predict stock closing prices using live market data fetched via `yfinance`. Built during my internship at **Corizo**, this project walks through the full ML pipeline on Reliance Industries (RELIANCE.NS) historical stock data from 2018.

---

## 📌 Project Summary

Stock price prediction is a classic time-series problem with real-world financial relevance. This project covers data fetching, exploratory data analysis, model training, and evaluation — using OHLCV (Open, High, Low, Close, Volume) stock data fetched live from Yahoo Finance.

---

## 📂 Dataset

| Field | Details |
|---|---|
| **Source** | Yahoo Finance via `yfinance` API |
| **Ticker** | RELIANCE.NS (Reliance Industries, NSE) |
| **Period** | 2018 (Jan – Dec) |
| **Records** | 245 trading days |
| **Features** | `Date`, `Open`, `High`, `Low`, `Volume` |
| **Target** | `Close` price |

---

## 🧪 Model

| Model | Notes |
|---|---|
| Linear Regression | Trained on 75% data, tested on 25% holdout set |

---

## 📊 Evaluation Metrics

| Model | RMSE | R² Score |
|---|---|---|
| Linear Regression | 2.80 | 0.9973 |

> An R² of 0.9973 means the model explains 99.73% of the variance in closing prices — strong performance for a linear baseline on this dataset.

---

## 🛠️ Tech Stack

- **Language:** Python 3.x
- **Libraries:** `yfinance`, `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/PariShahh/Minor-Project.git
cd Minor-Project
```

### 2. Install dependencies
```bash
pip install yfinance pandas numpy scikit-learn matplotlib seaborn jupyter
```

### 3. Launch the notebook
```bash
jupyter notebook Minor-Project.ipynb
```

---

## 📁 Repository Structure

```
Minor-Project/
│
├── Minor-Project.ipynb   # Main notebook
└── README.md
```

---

## 👩‍💻 Author

**Pari Shah** — Data Scientist  
📍 Mumbai | AudvikLabs  
🔗 [GitHub](https://github.com/PariShahh)

---

## 📝 Acknowledgements

- Internship project completed at **Corizo**
- Live data sourced from Yahoo Finance via the `yfinance` library
