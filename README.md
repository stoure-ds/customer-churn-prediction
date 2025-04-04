# customer-churn-prediction
Predicts which telecom customers are likely to leave the service using classification models. The goal is to help reduce churn by identifying high-risk customers based on behavior and service features.

# 🧠 Customer Churn Prediction

This project aims to predict customer churn (non-renewal) using real customer behavior and service data. By identifying high-risk customers, the company can take proactive steps to retain them and reduce churn-related losses.

---

## 📁 Dataset
- **Source**: `Customer renewal dataset.csv`
- **Rows**: 56,958
- **Features**: 37 (tenure, data usage, service calls, etc.)
- **Target**: `TARGET` (1 = renewed, 0 = churned)

---

## 💡 Objective
- Explore and clean the raw dataset
- Train and evaluate machine learning models to predict churn
- Identify key features that influence customer decisions
- Export results for business reporting

---

## 🧰 Tech Stack
- Python, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib
- Logistic Regression, Random Forest
- Jupyter Notebook

---

## 📊 Key Insights
- **Imbalanced data**: Only ~5% of customers renewed
- **Top predictors**: Tenure, monthly data usage, tech support calls
- **Random Forest AUC**: ~0.89

---

## 📂 Project Structure
