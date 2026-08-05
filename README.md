# 🛡️ IEEE-CIS Fraud Detection using LightGBM

## 🧠 Project Overview

Online payment fraud has become one of the biggest challenges in the financial industry. Detecting fraudulent transactions accurately while minimizing false positives is essential for protecting customers and reducing financial losses.

This project implements  **machine learning** for the **IEEE-CIS Fraud Detection** . The solution focuses on extensive **feature engineering**, handling **high-dimensional tabular data**, and training a **LightGBM** model with **Stratified K-Fold Cross Validation** to achieve strong predictive performance.

The final model was evaluated using the **Area Under the ROC Curve (AUC-ROC)**, the official evaluation metric of the competition.

---

## 📊 Dataset

**Competition:** IEEE-CIS Fraud Detection

**Source:** Kaggle

The dataset contains two major files:

* 💳 Transaction Data
* 👤 Identity Data

After merging both datasets, the model learns patterns that distinguish **fraudulent** from **legitimate** transactions.

---

## 🎯 Objective

Develop a robust fraud detection model that:

* ✅ Detects fraudulent transactions accurately
* ✅ Reduces false positives
* ✅ Handles missing values efficiently
* ✅ Works with high-cardinality categorical variables
* ✅ Generalizes well using Cross Validation

---

## 🛠️ Tech Stack

* 🐍 Python
* 📊 Pandas
* 🔢 NumPy
* 📈 Matplotlib
* 🎨 Seaborn
* 📚 Scikit-Learn
* ⚡ Google Colab

---

### Model Highlights

* 🚀 Gradient Boosting Decision Trees
* ⚡ Fast training
* 📉 Handles missing values natively
* 🌳 Efficient with large datasets
* 📊 Excellent performance on tabular data

---

# 🔄 Cross Validation

To obtain a reliable estimate of model performance, the project uses:

* ✅ Stratified K-Fold Cross Validation
* ✅ Out-of-Fold Predictions
* ✅ Averaged Test Predictions

This approach minimizes overfitting and produces a more stable evaluation.

---

# 📈 Evaluation Metric

Competition Metric:

## **ROC-AUC**

The project reports:

* 📌 Mean Cross Validation AUC
* 📌 Standard Deviation of AUC
* 📌 Out-of-Fold AUC

These metrics provide a comprehensive measure of the model's discrimination ability.

---

consider giving the repository a **Star ⭐**. It helps support the project and encourages further development.
