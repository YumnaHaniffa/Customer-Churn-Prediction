# 🛡️ Telco Customer Churn Prediction

**Predicting customer churn using Machine Learning**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yumna-prog/Customer-Churn-Prediction/blob/main/CustomerChurnPreduiction.ipynb)
[![GitHub](https://img.shields.io/badge/GitHub-Repo-black?logo=github)](https://github.com/yumna-prog/Customer-Churn-Prediction)
[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)](https://www.python.org/)

---
## 📋 Project Overview

Can we **predict which customers will cancel** their telecom subscription before they leave?

This project tackles a real-world **binary classification problem** using the famous **Telco Customer Churn** dataset. I built, tuned, and compared two supervised models:

- **Decision Tree Classifier** (highly interpretable)
- **Neural Network** (using Keras/TensorFlow + Keras Tuner)

Everything was developed following industry-standard practices: thorough EDA, advanced preprocessing, hyperparameter tuning, SMOTE for class imbalance, and a full ethical review.

**Live Demo**: [Open in Google Colab](https://colab.research.google.com/github/yumna-prog/Customer-Churn-Prediction/blob/main/CustomerChurnPreduiction.ipynb)  

---

## 🎯 Key Highlights

- ✅ Comprehensive **Exploratory Data Analysis** with insightful visualizations  
- ✅ Robust **data preprocessing** pipeline (missing values, encoding, scaling, SMOTE)  
- ✅ Hyperparameter tuning for both models  
- ✅ Full model comparison using Accuracy, Precision, Recall, F1, ROC-AUC & Confusion Matrices  
- ✅ **Neural Network outperformed** the Decision Tree   
- ✅ Full source code in appendix + Git-tracked development

## 📊 Dataset

- **Name**: Telco Customer Churn  
- **Source**: [Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn)  
- **Samples**: 7,043 customers  
- **Features**: 20+ (demographics, services, contract, charges, tenure, etc.)  
- **Target**: `Churn` (Yes / No) — **imbalanced** (≈26% churn)

---                                                                                                                          ## 🛠️ Technologies & Libraries

| Category           | Tools |
|--------------------|-------|
| Data Handling      | Pandas, NumPy |
| Visualization      | Matplotlib, Seaborn |
| Preprocessing      | Scikit-learn, imbalanced-learn (SMOTE) |
| Models             | DecisionTreeClassifier, TensorFlow/Keras |
| Hyperparameter Tuning | Keras Tuner, RandomizedSearchCV |
| Evaluation         | Scikit-learn metrics |
| Environment        | Google Colab, Git |

---         

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yumna-prog/Customer-Churn-Prediction.git
   cd Customer-Churn-Prediction
