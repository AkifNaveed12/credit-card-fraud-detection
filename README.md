# Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using
machine learning techniques on a highly imbalanced dataset.

---

## 🔍 Project Overview
- **Problem Type:** Binary Classification (Fraud vs Non-Fraud)
- **Challenge:** Extreme class imbalance
- **Objective:** Maximize fraud detection recall while maintaining reasonable precision

---

## 📊 Dataset
The dataset contains anonymized credit card transactions with:
- `Time` – seconds elapsed between transactions
- `Amount` – transaction amount
- `V1`–`V28` – anonymized PCA-transformed features
- `Class` – target label (0 = Non-Fraud, 1 = Fraud)

---

## 🧠 Approach
1. Exploratory Data Analysis (EDA)
2. Class distribution analysis & visualization
3. Log transformation of transaction amounts
4. Train-test split with stratification
5. Feature scaling using StandardScaler
6. Baseline modeling
7. Class imbalance handling using SMOTE
8. Model comparison:
   - Logistic Regression
   - Random Forest
   - Gradient Boosting

---

## 📈 Model Evaluation Metrics
- Precision
- Recall (primary focus)
- F1-score
- ROC-AUC

---

## 🏆 Results
- **Gradient Boosting** achieved the highest fraud recall
- **Random Forest** showed strong overall balance
- Demonstrates the importance of imbalance-aware modeling

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

---

## 👤 Author
**Akif Naveed**  
AI Engineering Student | Machine Learning Enthusiast
