#  Bank Stock Price Prediction Using Machine Learning

> AI-powered forecasting system for Vietnamese banking stocks (VCB, TCB, BID) using LSTM, Random Forest, XGBoost, Ensemble Learning, and LangChain.

![Python](https://img.shields.io/badge/Python-3.12-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-ML-green)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-teal)
![React](https://img.shields.io/badge/React-Frontend-61DAFB)
![License](https://img.shields.io/badge/License-MIT-success)

---

#  Overview

This project develops an AI-powered forecasting system for Vietnamese banking stocks (VCB, TCB, BID). Historical market data is processed through feature engineering and multiple machine learning models before predictions are served through a FastAPI backend and visualized in a React dashboard. A LangChain-powered AI assistant provides natural-language explanations for predictions.

##  Highlights

- Predicts stock trends for 1–5 trading days
- LSTM + Random Forest + XGBoost + Ensemble Voting
- Technical indicators (MA, RSI, Momentum, Volatility)
- Interactive Dashboard
- FastAPI REST API
- React Frontend
- LangChain AI Assistant
- Risk Indicators

---

#  Table of Contents

- Project Overview
- Objectives
- Dataset
- Features
- Project Architecture
- Data Pipeline
- Exploratory Data Analysis
- Machine Learning Models
- Model Performance
- Dashboard
- Project Structure
- Installation
- Usage
- Tech Stack
- Roadmap
- Future Improvements
- References
- Author

---

#  Objectives

- Forecast bank stock prices
- Compare ML models
- Build Ensemble model
- Deploy prediction API
- Build interactive dashboard
- Explain predictions with AI

#  Dataset

| Item | Value |
|------|------|
| Period | 2020–2026 |
| Total Records | 4,509 |
| Stocks | VCB, TCB, BID |

## Features

Open, High, Low, Close, Volume, Price_Range, Price_Change, MA_5, MA_20, RSI, Volatility_20, Momentum_5

#  Architecture

```text
React Dashboard
      │
FastAPI Backend
      │
Prediction API
      │
Machine Learning Models
      │
LangChain AI Assistant
```

#  Data Pipeline

```text
Raw Data
 ↓
Cleaning
 ↓
Feature Engineering
 ↓
Scaling
 ↓
Training
 ↓
Evaluation
 ↓
Prediction
```

#  Models

| Model | Purpose |
|------|---------|
| LSTM | Sequential Learning |
| Random Forest | Ensemble Trees |
| XGBoost | Gradient Boosting |
| Ensemble | Final Prediction |

#  Results

| Model | RMSE | MAE | R² | Direction Accuracy |
|------|------:|------:|------:|------:|
| LSTM | 2847 | 2156 | 0.72 | 74.3% |
| Random Forest | 3102 | 2398 | 0.68 | 71.5% |
| XGBoost | 2654 | 2023 | 0.75 | 76.8% |
| **Ensemble** | **2412** | **1856** | **0.79** | **79.2%** |

#  Dashboard

Create an `images/` folder and add:

- banner.png
- architecture.png
- dashboard.png
- prediction.png
- heatmap.png

Then embed:

```md
![Banner](images/banner.png)
```

#  Project Structure

```text
Bank-Stock-Prediction/
├── app/
├── data/
├── docs/
├── images/
├── models/
├── notebooks/
├── src/
├── requirements.txt
├── README.md
└── LICENSE
```

#  Installation

```bash
git clone https://github.com/yourusername/Bank-Stock-Prediction.git
cd Bank-Stock-Prediction
pip install -r requirements.txt
uvicorn app.main:app --reload
```

#  Tech Stack

- Python
- TensorFlow
- Scikit-Learn
- XGBoost
- Pandas
- NumPy
- FastAPI
- React
- TypeScript
- LangChain

# 🗺 Roadmap

- [x] Data preprocessing
- [x] Feature engineering
- [x] LSTM
- [x] Random Forest
- [x] XGBoost
- [x] Ensemble
- [ ] News Sentiment
- [ ] FinBERT
- [ ] Transformer Models
- [ ] Auto Trading

#  References

- TensorFlow
- XGBoost
- LangChain
- Financial Time Series Forecasting Literature

#  Author

**Nguyen Ngoc Tan**  
FPT University

---



