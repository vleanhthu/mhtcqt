# Credit Risk Scoring & Default Prediction | R

This project applies statistical and machine learning methods to assess creditworthiness and predict default risk using customer-level credit data. The objective is to assist financial institutions in making data-driven lending decisions by evaluating multiple modeling approaches and scoring systems.

## 📌 Objectives

- Predict the probability of default for individual credit card holders.
- Develop credit scoring models to classify risk levels.
- Compare the performance of various predictive models to identify the most reliable.

## 📁 Project Structure

- `data.credit.approval.xlsx`: Cleaned credit card default dataset used for modeling.
- `risk2.Rmd`: Includes the full codebase for data preprocessing, model training, evaluation, and credit scoring.
- `risk.management.2.pdf`: Final report detailing the methodology, results, and model comparison.

## 🛠 Methods Used

- **Logistic Regression** (with and without Weight of Evidence transformation)
- **Random Forest** for ensemble classification
- **K-Means Clustering** for customer segmentation
- **WOE (Weight of Evidence)** and **Information Value (IV)** for feature transformation and variable selection
- Evaluation metrics: Accuracy, AUC, Sensitivity, Specificity, Gini index

## ✅ Results Summary

- Logistic Regression with WOE and IV-based feature selection achieved the highest AUC (0.7424).
- Random Forest and KNN showed stable accuracy (~80%) but lower sensitivity in detecting defaulters.
- Credit scores were generated and visualized using histogram analysis.
- Logistic-based models recommended for best overall performance in identifying risky customers.

---
