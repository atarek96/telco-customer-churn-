# Telco Customer Churn Prediction

<img width="274" height="184" alt="download" src="https://github.com/user-attachments/assets/8e32858b-75e9-4a18-b050-045e8e570c53" />

## 📋 Project Overview

This project analyzes and predicts customer churn for a telecommunications company using machine learning. By identifying customers at high risk of leaving, the business can implement targeted retention strategies to reduce churn and maximize revenue.

**Key Objectives:**
- Perform exploratory data analysis (EDA) to understand churn patterns
- Build and compare multiple ML models for churn prediction
- Identify key churn drivers using SHAP explainability
- Quantify revenue-at-risk and prioritize high-value customers
- Provide actionable business recommendations

## 📊 Dataset

The dataset is from [Kaggle - Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn).

- **File**: `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- **Rows**: 7043 customers
- **Columns**: 21 features including demographics, services, contract details, and churn label
- **Target Variable**: `Churn` (Yes/No)

**Key Features:**
- `tenure`: Months with the company
- `MonthlyCharges` & `TotalCharges`
- `Contract`: Month-to-month, One year, Two year
- `PaymentMethod`, `InternetService`, etc.
- Customer demographics: gender, SeniorCitizen, Partner, Dependents

## 🛠️ Technologies & Libraries

- **Data Analysis**: Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn, XGBoost
- **Explainability**: SHAP
- **Environment**: Python 3, Jupyter Notebook
- **Visualization**: Plotly / Seaborn

## 📁 Project Structure

Telco-Customer-Churn/

├── Telco_Customer_Churn.ipynb     # Main Jupyter Notebook

├── WA_Fn-UseC_-Telco-Customer-Churn.csv  # Dataset

├── README.md

├── requirements.txt

└── outputs/



## 🚀 How to Run

### Prerequisites

1. Clone the repository:
   ```bash
   git clone https://github.com/atarek96/telco-customer-churn-/
   cd Telco-Customer-Churn
