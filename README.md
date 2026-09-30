# 📦 Inventory Demand Prediction

An AI-powered **Inventory Demand Prediction and Risk Analysis** system that uses historical sales and inventory data to predict future product demand and identify potential inventory shortages.

The project compares three machine learning approaches:

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

The trained models are integrated into an interactive **Streamlit dashboard** for demand prediction, model comparison, and data analytics.

---

## 🚀 Features

- 📊 Historical sales and inventory data analysis
- 🔮 Future demand prediction
- 🤖 Multiple Machine Learning models
- 📈 Model performance comparison
- ⚠️ Inventory risk detection
- 📦 Current inventory vs predicted demand analysis
- 📊 Interactive charts and visualizations
- 🖥️ Streamlit web dashboard
- 💾 Pre-trained models using Joblib

---

## 🧠 Machine Learning Models

The project uses three regression models:

### 1. Linear Regression
A basic regression model used as a baseline for demand prediction.

### 2. Random Forest Regressor
An ensemble learning model that combines multiple decision trees to improve prediction performance.

### 3. XGBoost Regressor
A gradient boosting model used for high-performance demand prediction.

---

## 📊 Model Performance

The models were evaluated using **R² Score** and **Mean Squared Error (MSE)**.

| Model | R² Score | MSE |
|---|---:|---:|
| Linear Regression | 0.7819 | 481.64 |
| Random Forest | 0.8708 | 285.37 |
| XGBoost | 0.8859 | 251.95 |

XGBoost achieved the highest R² score among the three trained models in the project's evaluation.

> Note: R² indicates how much of the variation in demand is explained by the model. It should not be interpreted as classification accuracy.

---

## 📁 Project Structure

```text
Inventory-Demand-Prediction/
│
├── app.py
├── sales_data.csv
├── linearModel.pkl
├── randomforest.pkl
├── xgboost.pkl
├── requirements.txt
└── README.md
