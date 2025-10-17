# classification_hackathone_Mlproject




---

# 🧠 Stroke Risk Prediction with Machine Learning — Project Overview

## 📌 Objective

This project focuses on **predicting the likelihood of stroke in individuals** based on their **health, lifestyle, and demographic attributes**.
Using **machine learning models**, we aim to identify major risk contributors and build a **predictive system to support early medical intervention**.

The dataset includes **5,110 patient records** with **12 important features**, including age, gender, BMI, hypertension, heart conditions, glucose levels, and smoking status.
The target variable **stroke** indicates whether a person had a stroke (1) or not (0).

---

## 🔄 Workflow & Approach

### ✅ 1. Data Preprocessing

* Loaded and inspected the dataset.
* Handled missing BMI values using the **mean**.
* Removed any **duplicate rows**.
* Converted categorical features to numeric using **LabelEncoder**.
* Applied **SMOTE (Synthetic Minority Oversampling Technique)** to balance the dataset, as stroke cases were rare.

---

### ✅ 2. Exploratory Data Analysis (EDA)

* Used **Matplotlib and Seaborn** for visual analysis.
* Generated **correlation heatmaps** to detect feature relationships.
* Identified that **age, hypertension, and glucose levels** have strong influence on stroke occurrence.

---

### ✅ 3. Model Building

Six different machine learning models were trained and compared:

1. Logistic Regression
2. Decision Tree
3. Random Forest ✅ *(Top Performer)*
4. Gradient Boosting
5. Support Vector Machine (SVM)
6. K-Nearest Neighbors (KNN)

The dataset was split into **80% training** and **20% testing** using `train_test_split` with **stratification** to keep the class ratio consistent.

---

### ✅ 4. Model Evaluation

Each model was evaluated with the following metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 🏆 Model Performance

| Model               | Accuracy   |
| ------------------- | ---------- |
| Logistic Regression | 0.7938     |
| Decision Tree       | 0.9044     |
| **Random Forest ✅** | **0.9424** |
| Gradient Boosting   | 0.8751     |
| SVM                 | 0.5111     |
| KNN                 | 0.8077     |

✅ **Random Forest Classifier delivered the highest accuracy (94.24%)**, and maintained a strong balance between precision and recall.

---

## 📈 Insights & Observations

* **Age, hypertension, and glucose levels** are the strongest predictors of stroke.
* **SMOTE improved model fairness** by handling class imbalance.
* **Ensemble models (Random Forest, Gradient Boosting)** outperformed single models due to better generalization.

---

## ✅ Final Conclusion

This project demonstrates how **machine learning can effectively predict stroke risks** by analyzing multiple health indicators.
The **Random Forest model** emerged as the most accurate and reliable solution, making it a strong foundation for **preventive healthcare systems and early warning tools**.

---

✅ Let me know if you want this converted into a **complete README.md file format with sections, code snippets, and proper styling**!
