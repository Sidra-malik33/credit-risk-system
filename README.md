# 💳 Credit Risk / Loan Approval System

## 📌 Problem
Digital banks need to decide whether to approve or reject loan applications using data.

## ⚙️ Solution
Built a machine learning system that:
- Predicts probability of default (PD)
- Applies business rules (Approve / Review / Reject)

## 🧠 Model
- Random Forest Classifier
- ROC-AUC: ~0.83
- Optimized to reduce false approvals

## 📊 Features
- Income-based features
- Loan ratios
- Credit history

## 🚀 API
Run:
uvicorn app:app --reload

Go to:
http://127.0.0.1:8000/docs

## 🔮 Output
- Probability of Default
- Decision (Approve / Review / Reject)

## 🛠 Tech Stack
- Python
- Scikit-learn
- FastAPI