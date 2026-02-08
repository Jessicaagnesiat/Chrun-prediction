# Customer Churn Prediction using Random Forest and SMOTE

## Overview
Customer churn is a critical challenge for telecommunication companies, as retaining existing customers is significantly more cost-effective than acquiring new ones.  
This project builds a machine learning model to predict customer churn by analyzing customer behavior, handling class imbalance, and evaluating model performance using robust metrics.

## Problem Statement
Customer churn data is highly imbalanced and influenced by multiple behavioral factors, making it difficult for businesses to accurately identify customers who are likely to leave.

## Objectives
- Predict customer churn using machine learning models  
- Handle class imbalance to improve churn detection  
- Compare model performance and select the most reliable model  
- Support data-driven customer retention strategies  

## Dataset
- **Source:** Telco Customer Churn Dataset  
- **Records:** 7,043 customers  
- **Features:** Demographics, services, contract details, billing, and charges  
- **Target Variable:** `Churn` (Yes / No)

## Methodology
1. **Exploratory Data Analysis (EDA)**
   - Analyzed churn distribution and customer behavior patterns
2. **Data Preprocessing**
   - Converted data types and handled missing values
   - Encoded categorical variables using Label Encoding
   - Scaled numerical features
3. **Handling Imbalanced Data**
   - Applied **SMOTE (Synthetic Minority Oversampling Technique)** to balance churn classes
4. **Modeling**
   - Trained and evaluated:
     - Random Forest Classifier
     - Decision Tree Classifier
5. **Model Evaluation**
   - Used K-Fold Cross Validation
   - Evaluation metrics: Precision, Recall, F1-score, Accuracy, ROC-AUC

## Model Performance
- **Best Model:** Random Forest (K-Fold)
- **Cross-Validation F1-score:** 0.85 (stable across folds)
- **Test Set Performance:**
  - Accuracy: 77.5%
  - Precision: 57%
  - Recall: 57.6%
  - F1-score: 57.5%
  - ROC-AUC: **0.82**

The high ROC-AUC score indicates strong capability in distinguishing churn and non-churn customers despite class imbalance.

## Results & Insights
- Random Forest outperformed Decision Tree in both performance and stability
- SMOTE significantly improved churn detection
- The model generalizes well to unseen data and is suitable for churn risk identification

## Business Impact
- Enables early identification of high-risk customers
- Supports targeted retention strategies
- Reduces customer acquisition costs
- Improves customer loyalty and long-term revenue

## Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib, Seaborn

## Conclusion
Random Forest combined with SMOTE provides a reliable and stable approach for customer churn prediction, offering valuable insights for proactive customer retention strategies.

## Author
Jessica Agnesia Tataung
