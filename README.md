# 🧠 Customer Churn Prediction

This project is a simple Machine Learning solution that predicts whether a customer will churn (i.e., leave a service) based on their account details, usage, and contract type. It is built using Python and Logistic Regression.

---

## 🔍 Problem Statement

Churn is a major problem for subscription-based businesses. This project uses customer data to **predict churn**, helping businesses take action before a customer leaves.

---

## 📁 Dataset

The dataset (`churn_dataset.csv`) includes:
- `tenure`: Number of months the customer has been with the company.
- `MonthlyCharges`: Amount charged to the customer monthly.
- `Contract`: Type of contract — Month-to-month, One year, Two year.
- `Churn`: Target variable (Yes/No).

---

## 🧪 Model Used

We used **Logistic Regression** because:
- It is efficient for binary classification problems like churn (Yes/No).
- Easy to interpret and quick to train.

---

## ⚙️ How It Works

1. Load the dataset.
2. Convert categorical values into numeric (Label Encoding).
3. Train the logistic regression model.
4. Predict churn based on input data.

---

## ✅ Requirements

- Python 3.x
- Pandas
- Scikit-learn

You can install dependencies using:
```bash
pip install pandas scikit-learn
