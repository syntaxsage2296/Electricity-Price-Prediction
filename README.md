# ⚡ PowerCast: Electricity Price Forecasting Challenge

## 📌 Project Overview
This project is part of the **PowerCast: The Electricity Price Forecasting Challenge**, focusing on predicting electricity prices using historical data and market-driven features. The model is designed to assist energy traders, grid operators, and policymakers in making informed decisions.

## 📊 Methodology
### **1️⃣ Data Collection & Preprocessing**
- **Source:** SMARD (Germany's electricity market platform)
- **Preprocessing Steps:** Missing value handling, feature engineering, time-series transformations.
- **Data Used:**
  - `processed_daily_data.csv`
  - `processed_hourly_data.csv`
  - `processed_weekly_data.csv`

### **2️⃣ Model Development**
- **Models Implemented:** Baseline models, LSTM, and ensemble learning.
- **Target Predictions:**
  - **Price Level Prediction** (Regression)
  - **Price Movement Direction** (Classification: Rise, Fall, Stable)

### **3️⃣ Evaluation Metrics** (Total: 25 Points)
- ✅ **Directional Accuracy (10 pts)** – Rise/Fall/Stable prediction accuracy.
- 📈 **Volatility Capture (10 pts)** – Ability to reflect observed price fluctuations.
- ⚠️ **Extreme Price Movement Detection (5 pts)** – Capturing sharp price spikes (>15% change).

## 🚀 Installation & Usage
### **1️⃣ Setup the Environment**
```bash
# Create a virtual environment
python -m venv venv

# Activate it
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt
```

### **2️⃣ Running the Model**
```bash
MARKET_PREDICTION_MODEL.ipynb
```

### **3️⃣ Model Evaluation**
```bash
MARKET_PREDICTION_MODEL.ipynb
```

## 📈 Results & Insights
- **High Directional Accuracy:** Achieved **99.74%** accuracy in predicting price movement.
- **Strong Volatility Capture:** Model effectively tracks market fluctuations (**99.75%** score).
- **Challenges in Extreme Price Detection:** Capturing sharp price spikes (**100%** score).