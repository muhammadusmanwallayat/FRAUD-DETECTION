# FRAUD-DETECTION 
# 🔍 Fraud Detection System (Machine Learning)

An end-to-end Machine Learning project built to detect fraudulent financial transactions using data preprocessing, feature engineering, SMOTE class balancing, and Random Forest modeling.

---

## 🚀 Features
- Realistic synthetic fraud dataset
- Full modular ML pipeline
- Handles imbalanced data with SMOTE
- Random Forest baseline model
- Saved model for real-time predictions
- Clean GitHub-ready structure

---

## 📁 Project Structure
fraud-detection-system/
├── data/ # dataset
├── models/ # saved trained model
├── notebooks/ # Jupyter EDA notebook
├── src/ # ML pipeline source code
└── main.py # prediction script


---

## 📊 Dataset Information
The dataset simulates legitimate and fraudulent transactions.

| Column | Description |
|--------|-------------|
| transaction_id | Unique identifier |
| amount | Transaction amount |
| oldbalanceOrg | Balance before transaction |
| newbalanceOrig | Balance after transaction |
| transaction_type | 0 = transfer, 1 = cash-out |
| is_fraud | 1 = fraud, 0 = legit |

---

## 🛠 Setup
Install dependencies:

```bash
pip install -r requirements.txt
