# ICU-Readmission-Prediction
Predicting early ICU readmission using machine learning on MIMIC data
Significance of the Problem

ICU discharge is a high-stakes decision: premature transfer raises the risk of readmission and mortality, while delays increase costs. Readmitted patients face twice the mortality risk, longer hospital stays, and increased resource utilization. Accurate prediction of high-risk patients can enable safer discharges and more efficient ICU management.

Potential Impact

By identifying patients at high risk for early ICU readmission, this project can help:

Reduce complications and prevent unnecessary readmissions

Optimize ICU resource utilization

Lower costs for hospitals and improve patient outcomes

Project Overview

This project implements machine learning models to predict early ICU readmission using a dataset of 3,000 encounters and 865 preprocessed features including demographics, chart events, laboratory measurements, and ICD-10 chapter indicators.

Data Preprocessing

Handled missing values

Encoded categorical variables

Scaled numerical features

Performed an 80/20 train–test split

Models Implemented

Logistic Regression

Random Forest

XGBoost

Each model was optimized using 5-fold GridSearch CV.

Model Evaluation

PR-AUC & ROC-AUC

Confusion matrices

Precision, Recall, and F1 scores (per class)
