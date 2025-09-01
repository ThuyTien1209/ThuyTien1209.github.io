---
title: "Stroke Risk Prediction"
summary: "Applied ML models (Decision Tree, SVM, Logistic Regression) to predict stroke risk using healthcare dataset."
share: false
tags:
  - Python
  - Machine Learning
  - Data Mining
date: "2025-05-26"
image:
  filename: "stroke.png"
---
### Project Overview
- Developed a predictive model for stroke risk using the **Stroke Prediction Dataset (Kaggle, 5110 patients)** containing demographic, clinical, and lifestyle factors.  
- Performed **data preprocessing**: handling missing values (BMI), encoding categorical variables, outlier detection, and balancing classes with **SMOTE + undersampling**.  
- Conducted **clustering** (K-Means, Hierarchical) to explore data patterns; Hierarchical achieved better separation (Silhouette ~0.46 vs 0.26).  

### Modeling
- Compared three supervised models: **Decision Tree, Support Vector Machine (SVM), Logistic Regression**.  
- Evaluated with **Accuracy, Precision, Recall, F1-score, AUC**, using **K-Fold Cross Validation (k=2,5,10)**.  

### Key Results
- **Decision Tree** outperformed others: Accuracy 88.1%, F1-score 0.88, Recall 0.76, Precision 0.88.  
- On test set (466 patients), achieved **90.3% prediction accuracy**.  
- Demonstrated balanced detection of stroke cases while minimizing false negatives.  

### Impact
This project shows how **machine learning can support early stroke risk screening**, enabling healthcare providers to better identify high-risk patients and allocate preventive resources effectively.
