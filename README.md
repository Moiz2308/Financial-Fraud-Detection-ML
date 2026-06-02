# 💳 Financial Fraud Detection ML System

> Machine Learning based Financial Fraud Detection System using Python, Random Forest, and Business Risk Analysis.

---

## 📌 Project Overview

Financial fraud causes billions of dollars in losses every year.  
This project builds an intelligent fraud detection system capable of identifying fraudulent financial transactions using Machine Learning techniques.

The solution focuses not only on model accuracy, but also on:
- Business impact
- Fraud risk analysis
- Feature importance
- Model evaluation
- Real-world deployment considerations

---

## 🚀 Key Highlights

✅ Processed over **6.3 million transaction records**

✅ Built an end-to-end Machine Learning pipeline

✅ Performed:
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Model Training
- Business Insight Generation

✅ Compared multiple ML models:
- Logistic Regression
- Random Forest Classifier

✅ Achieved extremely high fraud detection performance:
- ROC-AUC Score: **0.998**
- Near-perfect fraud identification

---

# 🧠 Problem Statement

The objective is to detect fraudulent financial transactions proactively using Machine Learning.

Challenges:
- Highly imbalanced dataset
- Large-scale transaction records
- Real-time fraud detection requirements
- Minimizing false positives

---

# 📂 Dataset Information

The dataset contains simulated financial transaction data over a 30-day period.

### Features Include:
- Transaction Type
- Transaction Amount
- Sender & Receiver Balances
- Fraud Labels
- Flagged Transactions

### Dataset Size
- Rows: **6,362,620**
- Columns: **11**

---

# ⚙️ Technologies Used

| Category | Tools |
|---|---|
| Language | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Environment | Google Colab, Jupyter Notebook |

---

# 📊 Exploratory Data Analysis

Key insights discovered during EDA:

- Fraud transactions are extremely rare
- CASH_OUT and TRANSFER transactions show higher fraud probability
- Transaction balance inconsistencies strongly indicate fraudulent behavior
- Certain engineered balance-error features became strong fraud predictors

---

# 🧹 Data Preprocessing

Performed:
- Missing value checks
- Duplicate handling
- Feature engineering
- Removal of ID-like columns
- Creation of balance difference features
- Data splitting for training/testing

---

# 🤖 Machine Learning Models

## 1️⃣ Logistic Regression
Used as baseline model for comparison.

### Performance:
- High Recall
- Lower Precision due to class imbalance

---

## 2️⃣ Random Forest Classifier
Final selected model.

### Why Random Forest?
- Handles non-linearity effectively
- Strong performance on imbalanced data
- Captures complex fraud patterns
- Robust against overfitting

### Final Performance:
| Metric | Score |
|---|---|
| ROC-AUC | 0.998 |
| Accuracy | 99.99% |
| Fraud Detection Recall | Excellent |

---

# 📈 Model Evaluation

Evaluation methods used:
- Classification Report
- Confusion Matrix
- ROC Curve
- Precision-Recall Curve
- Feature Importance Analysis

---

# 🔍 Key Fraud Drivers

Top important fraud indicators identified:
- Origin balance errors
- Sudden balance differences
- Transaction amount anomalies
- Transaction type patterns

These insights can help financial institutions improve fraud prevention strategies.

---

# 💼 Business Recommendations

### Recommended Actions:
- Monitor high-risk transaction patterns in real time
- Introduce automated fraud alert systems
- Apply additional verification for suspicious transactions
- Continuously retrain models using recent transaction data

---

# ⚠️ Model Limitations

The current model uses some post-transaction balance features that may not always be available in real-time systems.

Future improvements:
- Real-time streaming fraud detection
- Advanced ensemble methods
- Deep Learning models
- Production deployment pipeline

---

# 📁 Repository Structure

```bash
Financial-Fraud-Detection-ML/
│
├── notebook/
│   ├── fraud_detection_case_study.ipynb
│   └── fraud_detection_case_study.pdf
│
├── images/
│
├── README_assets/
│
└── README.md
```

---

# ▶️ How to Run

## 1. Clone Repository

```bash
git clone https://github.com/Moiz2308/Financial-Fraud-Detection-ML.git
```

## 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 3. Run Notebook

Open the notebook using:
- Jupyter Notebook
- Google Colab

---

# 📌 Future Scope

Potential future improvements:
- XGBoost implementation
- Real-time fraud scoring API
- Streamlit dashboard
- SHAP Explainability
- Cloud deployment

---

# 👨‍💻 Author

## Mohammed Moiz Sayyed

📧 Email: theagle290@gmail.com

🔗 LinkedIn:
www.linkedin.com/in/moizsayyed1

🔗 GitHub:
https://github.com/Moiz2308

---

# ⭐ If you found this project useful, consider giving it a star!
