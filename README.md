**IRFD: Electricity Fraud Detection with Feature-Engineered ML Ensemble**
📘 Paper Title: IRFD: A Feature Engineering based Ensemble Classification for Detecting Electricity Fraud in Traditional Meters
📅 Published at: 24th International Conference on Computer and Information Technology (ICCIT), 2021
🧠 Focus: Electricity theft detection using feature engineering and ensemble machine learning models.

📌 **Project Summary**
This repository contains the implementation of IRFD, a robust machine learning pipeline developed to detect non-technical electricity fraud in traditional metering systems. The method combines advanced feature engineering, outlier detection, and ensemble classification models to improve fraud detection accuracy on noisy and imbalanced datasets.

🧰 **Core Techniques Used**
Feature Engineering:
Recursive Feature Elimination with Cross-Validation (RFECV)
Isolation Forest for anomaly removal
StandardScaler for normalization
SVMSMOTE for data balancing

**Machine Learning Models:**
Random Forest (RF) 🌟 Best performance
XGBoost (XGB)
AdaBoost (ADA)
Gradient Boosting (GBC)
K-Nearest Neighbors (KNN)
Logistic Regression (LR)
Artificial Neural Network (ANN)

🧪 **Results Summary (Using RFECV)**
Model	Accuracy	Precision	Recall	F1-Score
Random Forest	97.06%	96%	98%	97%
XGBoost	96.96%	96%	98%	97%
ANN	93%	94%	92%	93%
KNN	95.87%	98%	94%	96%

**ROC-AUC:** Up to 0.993 (RF), 0.992 (XGB)

Class imbalance handled with SVMSMOTE.
Feature reduction improved performance and efficiency.

