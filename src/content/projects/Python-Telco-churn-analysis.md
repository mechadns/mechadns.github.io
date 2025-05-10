---
title: Telecom Customer Churn Prediction
description: A guided machine learning project using Kaggle data to predict customer churn. Trained and evaluated several models including Gradient Boosting and Voting Classifier.
publishDate: 2025-05-10
tags:
  - Machine Learning
  - Python
  - Classification
  - Telecom
  - Gradient Boosting
  - Churn Analysis
seo:
  image:
    src: /portfolio-churn.jpg
    alt: Telecom Churn Prediction Project
isFeatured: true
---

<p style="text-align: center;">
The GitHub repository for this project can be viewed <a href="https://github.com/mechadns/Telco-churn-prediction-main" target="_blank">here</a>.
</p>

# Telecom Customer Churn Prediction

This project applies supervised machine learning techniques to analyze and predict customer churn in the telecom sector. Using the [Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn), the goal was to identify key drivers of churn and build models capable of predicting whether a customer is likely to leave.

> 📌 **Note**: This is a guided learning project included in my portfolio to demonstrate my ability to execute an end-to-end data science pipeline.

---

## 🧠 Models Trained

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Support Vector Classifier (SVC)  
- Decision Tree Classifier  
- Random Forest Classifier  
- AdaBoost Classifier  
- Gradient Boosting Classifier  
- Voting Classifier (ensemble of selected models)

### 🏆 Best Performer
- **Gradient Boosting Classifier**
  - Accuracy: ~81%
  - ROC AUC: ~0.84

---

## 📂 Files in the Repository

| File | Description |
|:-----|:------------|
| `TelcoCustomerChurn.ipynb` | Full notebook containing EDA, preprocessing, and model evaluation |
| `WA_Fn-UseC_-Telco-Customer-Churn.csv` | Original dataset sourced from Kaggle |
| `README.md` | Full project documentation |

---

## 📈 Key Insights

- **Churn Rate**: ~26.6%  
- **High Risk Groups**: Month-to-month customers, electronic check users, new customers, and fiber optic users  
- **Tenure Matters**: Long-term customers are significantly less likely to churn  

---

## 🧪 Evaluation Metrics Used

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC AUC  
- Confusion Matrix  

---

## 🧰 Tools & Technologies

- Python 3.8+
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- Jupyter Notebook

---

## 🧺 Future Improvements

- Hyperparameter tuning with GridSearchCV  
- Feature importance visualization  
- Integration with customer support or feedback data  
- Deploy as a churn risk prediction tool using Streamlit or Flask

---