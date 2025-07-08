
# 📈 Hybrid AI Model for Stock Price Prediction

This project explores the use of a **hybrid AI architecture** to predict stock prices using three components:
- **LSTM (Long Short-Term Memory)** for sequential price forecasting,
- **FinBERT** for extracting financial sentiment from news/text data,
- **Random Forest** for robust ensemble prediction based on structured features.

The system was developed as part of the AI & Hyperautomation course at La Trobe University, aiming to combine traditional ML and deep learning with NLP insights.

---

## 🔍 Project Objectives

- Predict stock price movement (up/down or price value)
- Integrate text sentiment and historical price trends
- Compare model accuracy and explainability
- Develop a modular AI pipeline that can be expanded for financial forecasting

---

## 🧠 Technologies & Tools

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- TensorFlow/Keras for LSTM
- HuggingFace Transformers for FinBERT
- Scikit-learn for Random Forest and evaluation
- Jupyter Notebook (Colab or VS Code)

---

## 📁 Project Structure

```
📦 hybrid-stock-predictor/
├── data/
│   ├── prices.csv
│   └── news.csv
├── finbert_sentiment.py
├── lstm_model.py
├── rf_model.py
├── hybrid_pipeline.py
├── README.md
└── results/
    └── evaluation_metrics.csv
```

---

## 🔄 Workflow

1. **Data Loading** – Historical stock prices and relevant financial news
2. **Preprocessing** – Cleaning price data and extracting sentiment from news using FinBERT
3. **Feature Engineering** – Combine LSTM outputs and sentiment scores
4. **Model Training** – Train Random Forest with LSTM predictions + FinBERT sentiment
5. **Evaluation** – Accuracy, RMSE, and feature importance with SHAP

---

## 💡 Key Learnings

- FinBERT added valuable predictive signals from financial language.
- LSTM captured temporal price trends but overfitted without regularization.
- Random Forest boosted performance by fusing sentiment and LSTM patterns.
- Explainability tools like SHAP helped interpret model predictions.

---

## 📌 Next Steps

- Deploy as a real-time dashboard using Streamlit
- Add live news scraping via APIs (e.g., NewsAPI, Yahoo Finance)
- Incorporate technical indicators (RSI, MACD) for feature richness

---

## 🤝 Contributors

- Rashik Ahmed Khan  
- BUS5002 Group Members (La Trobe University)

---

## 📜 License

This project is for academic purposes only. Not financial advice.
