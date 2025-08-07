# CodeAlpha_CreditScoringModel

## 📝 Project Title: Credit Scoring Model (Classification)

### 🎯 Objective:
Build a predictive model to assess whether a credit card customer is likely to default on their payment next month using financial and behavioral data.


## 📁 Dataset Used:
- UCI Credit Card Dataset
- Columns: 25 features including `LIMIT_BAL`, `AGE`, `PAY_X`, `BILL_AMT`, `PAY_AMT`, etc.
- Target Variable: `default.payment.next.month` (1 = default, 0 = not default)


## 🔍 ML Models Applied:
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**

### ⚙️ Hyperparameter Tuning:
- Logistic Regression:
  - `C=1`, `max_iter=500`, `solver='lbfgs'`
- Decision Tree:
  - `max_depth=10`, `min_samples_split=10`
- Random Forest:
  - `n_estimators=200`, `min_samples_split=2`, `max_depth=None`

---

## 🧪 Test Set Results:

| Model               | Accuracy | ROC-AUC | Best For            |
|--------------------|----------|---------|----------------------|
| Logistic Regression| 67.13%   | 0.710   | Balanced baseline    |
| Decision Tree      | 75.03%   | 0.716   | Simpler rules-based  |
| **Random Forest**  | **79.72%** | **0.753** | ⭐️ **Best Performing** |

---

### 📊 Confusion Matrix for Best Model (Random Forest):

[[4178 495]
[ 722 605]]




## 🔝 Top 10 Important Features:
| Feature     | Importance |
|-------------|------------|
| PAY_0       | 0.1014     |
| LIMIT_BAL   | 0.0725     |
| ID          | 0.0566     |
| AGE         | 0.0536     |
| PAY_2       | 0.0518     |
| PAY_AMT1    | 0.0474     |
| BILL_AMT1   | 0.0467     |
| PAY_AMT2    | 0.0459     |
| PAY_AMT6    | 0.0456     |
| PAY_AMT3    | 0.0426     |



## 🔁 Cross-Validation (ROC-AUC):

| Model               | Mean ROC-AUC | Std Dev |
|--------------------|--------------|---------|
| Logistic Regression| 0.7356       | 0.0042  |
| Decision Tree      | 0.8226       | 0.0536  |
| Random Forest      | **0.9371**   | 0.0350  |

---

## ⚙️ Tech Stack:
- Python, Pandas, NumPy
- scikit-learn, imbalanced-learn (SMOTE)
- Matplotlib, Seaborn

---

## 🧠 Learnings:
- Hyperparameter tuning improves accuracy
- Feature importance helps interpret models
- Ensemble models like Random Forest are powerful for classification tasks



## 🔗 Deliverables:
- ✅ Source Code: [Link to this GitHub repo]
- ✅ Video Explanation: [YouTube or Drive link]
- ✅ LinkedIn Post: [Your LinkedIn post link]

---

## 🙋‍♂️ Author:
**Name:** [MD SOHAG HOSSAIN]  
**Role:** Machine Learning Intern @CodeAlpha  
**Date:** August 2025  
