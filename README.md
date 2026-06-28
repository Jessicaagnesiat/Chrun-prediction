# 🤖 Customer Churn Prediction using Machine Learning

> **Predicting customer churn using Machine Learning to help businesses identify at-risk customers and improve customer retention strategies.**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)

---

# 📌 Project Overview

Customer churn is one of the biggest challenges for subscription-based businesses because losing existing customers directly impacts recurring revenue and increases customer acquisition costs.

This project develops an end-to-end machine learning pipeline to predict customers who are likely to churn. The analysis includes data preprocessing, imbalance handling using SMOTE, model comparison, cross-validation, and performance evaluation to identify the most reliable predictive model.

---

# 🎯 Business Problem

Businesses often struggle to identify customers who are likely to discontinue their services. Without an accurate churn prediction model, customer retention campaigns become reactive instead of proactive, resulting in higher customer acquisition costs and lost revenue.

---

# 🎯 Project Goals

- Predict customers who are likely to churn.
- Handle imbalanced customer data using SMOTE.
- Compare multiple classification models.
- Evaluate model performance using cross-validation and test data.
- Select the most stable and accurate model.
- Support customer retention strategies through predictive analytics.

---

# 📂 Dataset

**Telco Customer Churn Dataset**

The dataset contains customer demographic information, subscription details, billing information, and service usage collected from a telecommunications company.

### Target Variable

- **Churn**
  - Yes
  - No

### Dataset Features

- Customer demographics
- Contract type
- Payment method
- Internet services
- Monthly charges
- Total charges
- Customer tenure
- Additional service subscriptions

---

# 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 🔍 Analysis Techniques

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Missing Value Handling
- Label Encoding
- Feature Scaling
- SMOTE Oversampling
- Random Forest Classification
- Decision Tree Classification
- Cross Validation
- K-Fold Cross Validation
- Model Evaluation
- ROC Curve Analysis

---

# 🏗️ Project Workflow

```text
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
EDA
      │
      ▼
Missing Value Handling
      │
      ▼
Label Encoding
      │
      ▼
SMOTE Oversampling
      │
      ▼
Feature Scaling
      │
      ▼
Random Forest
      │
      ▼
Decision Tree
      │
      ▼
Cross Validation
      │
      ▼
Model Evaluation
      │
      ▼
Business Recommendation
```

---

# 📊 Model Performance

| Metric | Random Forest |
|---------|--------------:|
| Accuracy | **77.50%** |
| Precision | **57.49%** |
| Recall | **57.64%** |
| F1-Score | **57.56%** |
| ROC-AUC | **82.42%** |

---

# 🔍 Key Findings

- Customer churn data was highly imbalanced and required SMOTE oversampling.
- Random Forest consistently outperformed Decision Tree in overall classification performance.
- K-Fold Cross Validation achieved an average F1-score of **84.9%** with very low standard deviation, indicating strong model stability.
- The final Random Forest model achieved a **ROC-AUC score of 82.42%**, demonstrating good discrimination between churn and non-churn customers.
- The model can serve as an effective early warning system for identifying customers at high risk of churning.

---

# 💡 Business Recommendations

| Recommendation | Business Value |
|---------------|----------------|
| Identify customers with high predicted churn probability. | Enable proactive customer retention initiatives before customers leave. |
| Offer personalized retention campaigns. | Increase customer engagement and reduce churn rates. |
| Provide loyalty rewards or exclusive offers to high-risk customers. | Improve customer lifetime value (CLV). |
| Monitor churn predictions regularly using updated customer data. | Support proactive and data-driven business decisions. |
| Retrain the prediction model periodically. | Maintain prediction accuracy as customer behavior evolves. |

---

# 🚀 Business Impact

This project demonstrates how predictive analytics can help businesses:

- Reduce customer churn.
- Improve customer retention.
- Increase customer lifetime value.
- Lower customer acquisition costs.
- Support data-driven marketing and customer relationship strategies.

---

# 🧠 Skills Demonstrated

- Machine Learning
- Classification Modeling
- Random Forest
- Decision Tree
- SMOTE
- Feature Engineering
- Cross Validation
- K-Fold Validation
- Model Evaluation
- ROC Curve Analysis
- Predictive Analytics

---

# 📊 Visualizations

- Customer Churn Distribution
- ROC Curve
- Confusion Matrix
- Model Performance Comparison
- Feature Importance

---

# 📁 Repository Structure

```text
Customer-Churn-Prediction
│
├── notebook/
│   └── Customer_Churn_Prediction.ipynb
│
├── images/
│   ├── churn_distribution.png
│   ├── roc_curve.png
│   ├── confusion_matrix.png
│   ├── feature_importance.png
│   └── model_comparison.png
│
└── README.md
```

---

# 👩‍💻 Author

**Jessica Agnesia Tataung**

- LinkedIn: https://www.linkedin.com/in/jessicaagnesiat/

🌐 Portfolio Website

https://jessicaagnesiat.github.io/portofolio-data-scientist/

---

⭐ If you found this project useful, feel free to give it a star!
