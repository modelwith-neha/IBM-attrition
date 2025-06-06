# 📊 Employee Attrition Prediction

**Domain**: Human Resources Analytics  
**Dataset Used**: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset   
**Problem Type**: Classification and Clustering   
**Tools**: Python (Pandas, Scikit-learn), Jupyter Notebook, SMOTE, Plotly, Tableau

---

## 📌 Project Overview

Employee attrition—especially unexpected exits—can be costly for organizations in terms of talent, morale, and productivity. The goal of this project is to build robust machine learning models to **predict which employees are likely to leave**, enabling HR teams to take proactive measures.

We used a real-world HR dataset containing 1470 records and 35 features, focused on demographic, compensation, satisfaction, and performance-related variables.

---

## 🛠️ Key Techniques

### 📋 Data Preprocessing
- **Missing Values**: Imputed with mean (numeric) and mode (categorical)
- **Encoding**: Label encoding for categorical features
- **Scaling**: MinMaxScaler for normalization
- **Class Imbalance**: Resolved using SMOTE

### 🔍 Models Used
- Logistic Regression (Forward & Backward Selection)
- Decision Tree
- Naïve Bayes
- Support Vector Machine (SVM)
- Neural Network (MLP Classifier)
- Random Forest
- Gradient Boosting and XGBoost
- KNN
- Ensemble Methods (Voting and Bagging)
- KMeans and Agglomerative Clustering (for exploratory insights)

---

## 🏆 Top Performing Models

| Model              | Accuracy | Recall | AUC   |
|-------------------|----------|--------|-------|
| Gradient Boosting | 90.0%    | 91.9%  | 0.970 |
| XGBoost           | 90.0%    | 90.2%  | 0.970 |
| SVM (C=10)        | 91.9%    | 90.3%  | 0.966 |
| KNN               | 82.6%    | 92.3%  | 0.898 |

---

## 📈 Key Business Insights
- Employees with **higher job involvement** and **stock options** are significantly less likely to leave.
- **Overtime** and **longer commutes** increase attrition risk.
- **Lack of recent promotions** is a strong indicator of potential departure.
- **Gradient Boosting** provided the best combination of accuracy and interpretability.

---

## 📂 Repository Structure

- `Final_ML.ipynb` — Main Jupyter Notebook with preprocessing, modeling, and evaluation
- `Final_PPT.pdf` — Summary of business problem, methodology, insights, and model performance
- `data/` — Placeholder for original or anonymized dataset
- `images/` — Visuals and charts used in the presentation


## 📬 Contact

For questions, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/neha-tiwarii/).

---
