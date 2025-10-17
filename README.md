
🧠 Stroke Prediction using Machine Learning
✅ Table of Contents
✅ Dataset Description
✅ Project Workflow
✅ Installation & Usage Instructions
✅ Project Structure
✅ Future Improvements & Contributions
✅ License & Contact

---

# 🧠 Stroke Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

## 📌 Table of Contents

* [Project Overview](#project-overview)
* [Dataset Information](#dataset-information)
* [Features](#features)
* [Project Workflow](#project-workflow)
* [Exploratory Data Analysis](#exploratory-data-analysis)
* [Modeling](#modeling)
* [Results](#results)
* [Installation](#installation)
* [Usage](#usage)
* [Project Structure](#project-structure)
* [Key Findings](#key-findings)
* [Future Improvements](#future-improvements)
* [Contributions](#contributions)
* [License](#license)
* [Contact](#contact)

---

## 📋 Project Overview

Stroke is a major cause of death and disability worldwide. Early prediction can help in timely prevention and treatment.
This project applies **machine learning algorithms** to predict whether a patient is likely to experience a **stroke** based on **medical, demographic, and lifestyle factors**.

✅ Goal: Build a predictive model to classify stroke risk
✅ Outcome: Identify key stroke factors + deploy best performing model

---

## 📊 Dataset Information

* **Total Records:** 5,110 patients
* **Features (12):**

  * Gender
  * Age
  * Hypertension
  * Heart Disease
  * Ever Married
  * Work Type
  * Residence Type
  * Average Glucose Level
  * BMI
  * Smoking Status
* **Target Variable:**

  * `stroke` → 1 = Stroke, 0 = No Stroke

✅ Identified **class imbalance** → Applied **SMOTE** to balance data.

---

## ✅ Features

✔ Data Preprocessing & Cleaning
✔ Exploratory Data Analysis (EDA)
✔ Feature Encoding & SMOTE
✔ Multiple ML Models
✔ Evaluation Metrics (Accuracy, Precision, Recall, F1, Confusion Matrix)
✔ Best Model: Random Forest (94.24% Accuracy)

---

## 🔄 Project Workflow

1️⃣ Data Loading
2️⃣ Data Cleaning → Missing values, duplicates
3️⃣ Encoding Categorical Data
4️⃣ SMOTE for class balancing
5️⃣ EDA & correlations
6️⃣ Train-Test Split (80/20 with stratification)
7️⃣ Model Training (6 algorithms)
8️⃣ Model Evaluation
9️⃣ Best Model Selection
🔟 Conclusion & Insights

---

## 📈 Exploratory Data Analysis

* Heatmaps to identify correlations
* Age distribution by stroke
* Hypertension vs Stroke
* Glucose Level patterns
* Smoking status comparison

**Key Observations:**

* Older individuals have higher stroke rate
* Hypertension & high glucose levels strongly linked to stroke
* Smoking has moderate impact

---

## 🤖 Modeling

| Algorithm           | Performance                     |
| ------------------- | ------------------------------- |
| Logistic Regression | ✅ Good baseline                 |
| Decision Tree       | ✅ High accuracy but overfitting |
| Random Forest       | 🌟 Best overall                 |
| Gradient Boosting   | 🔄 Good performance             |
| SVM                 | ❌ Poor (<60%)                   |
| KNN                 | ✅ Decent                        |

**Evaluation Metrics Used:**

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 🏆 Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 0.7938   |
| Decision Tree       | 0.9044   |
| Random Forest ✅     | 0.9424   |
| Gradient Boosting   | 0.8751   |
| SVM                 | 0.5111   |
| KNN                 | 0.8077   |

✅ **Winner: Random Forest (94.24% Accuracy)**
✅ Best balance between recall & precision
✅ Excellent generalization

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/your-username/stroke-prediction.git

# Navigate into project
cd stroke-prediction

# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate  # (Windows: venv\Scripts\activate)

# Install dependencies
pip install -r requirements.txt
```

---

## 🚀 Usage

```bash
# Run the notebook
jupyter notebook Stroke_Prediction.ipynb
```

or if you have a script:

```bash
python stroke_prediction.py
```

---

## 📂 Project Structure

```
📦 stroke-prediction
├── 📁 data
│   └── stroke_data.csv
├── 📁 notebooks
│   └── Stroke_Prediction.ipynb
├── 📁 models
│   └── random_forest_model.pkl
├── 📄 stroke_prediction.py (optional)
├── 📄 README.md
└── 📄 LICENSE
```

---

## 📌 Key Findings

✅ Age, hypertension, and glucose level are the most critical factors.
✅ SMOTE significantly improved fairness and predictive performance.
✅ Ensemble models (Random Forest, Gradient Boosting) outperform basic models.
✅ SVM struggled due to nonlinear separability & scaling issues.

---

## 🔮 Future Improvements

🚀 Hyperparameter tuning for better results
🚀 Add deep learning models
🚀 Build a Flask / Django web app
🚀 Deploy model using Streamlit or FastAPI
🚀 Use real-time health monitoring data (IoT/wearables)

---

## 🤝 Contributions

Contributions are welcome!
Feel free to:

* Open an issue
* Fork the repository
* Submit a pull request

---

## 📜 License

This project is licensed under the **MIT License**.
You are free to use, modify, and distribute this project.

---



---

✅ Let me know if you want me to:

* Add a **Streamlit web app** for predictions
* Create a **model.pkl** and **inference script**
* Write a **Project Report / PPT**
* Build a **Dashboard** with visualizations

👉 Just say the word, I’ll do it!
