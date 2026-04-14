# 🚀 Food Demand Forecasting & Promotion Optimization

## 📌 Overview

This project predicts weekly food demand using machine learning and provides actionable business recommendations for pricing and promotions.

It simulates real-world business decision-making for inventory and marketing optimization.

---

## ⚙️ Features

* 📊 Data preprocessing & feature engineering
* 🤖 Multiple ML model comparison:

  * Linear Regression
  * Random Forest
  * Gradient Boosting
  * XGBoost
  * LightGBM
  * CatBoost (Final Model)
* 🔧 Hyperparameter tuning (GridSearch)
* 📈 Interactive dashboard using ipywidgets
* 💡 Business recommendations engine
* 📉 Price vs Demand simulation

---

## 🧠 Final Model

**CatBoost Regressor (Tuned)**

* R² Score: ~0.49
* Best Parameters:

  * depth = 6
  * iterations = 500+
  * learning_rate = 0.1

---

## 📊 Dashboard Capabilities

* Adjust:

  * Price
  * Base Price
  * Week
  * Promotion
  * Homepage Feature
* Predict demand instantly
* Get:

  * Demand insights
  * Business recommendations
  * Price-demand visualization curve

---

## 📂 Dataset

* File: `Food demand.csv`
* Includes:

  * Pricing details
  * Promotions
  * Weekly demand
  * Product-level data

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* CatBoost, XGBoost, LightGBM
* Matplotlib
* ipywidgets

---

## ▶️ How to Run

Install dependencies:

```bash
pip install -r requirements.txt
```

Run notebook:

```
Food_Demanding_Forecasting_Dashboard.ipynb
```

---

## 💡 Key Insights

* Demand decreases as price increases
* Promotions significantly boost demand
* Feature engineering improves model performance
* CatBoost outperformed other models

---

## 🚀 Future Improvements

* Deploy as Streamlit web app
* Add time-series forecasting (LSTM / ARIMA)
* Real-time pricing optimization
* Multi-product recommendation system

---

## 👨‍💻 Author

**Punith Kumar**
