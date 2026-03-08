# 📌 Employee Attrition Prediction & Salary Hike Recommendation System

## 📖 Project Overview

Employee attrition is a major challenge for organizations as it leads to increased hiring costs, productivity loss, and workforce instability.

This project develops a **Machine Learning–based HR Decision Support System** that:

* Predicts employee attrition (**Yes / No**)
* Generates **attrition risk scores**
* Recommends **salary hike percentages**
* Explains predictions using **SHAP (Explainable AI)**

The system helps HR departments make **proactive, transparent, and data-driven retention decisions**.

---

## 🎯 Problem Statement

Organizations often face difficulty in:

* Identifying employees who are likely to leave
* Understanding the **key factors influencing attrition**
* Making **fair and optimized salary hike decisions**
* Trusting **black-box machine learning models**

This project aims to solve these challenges using **predictive analytics and explainable AI techniques**.

---

## 🚀 Proposed Solution

The system consists of the following components:

### 1️⃣ Classification Model (Random Forest)

* Predicts **employee attrition**
* Generates **risk categories** such as **Low, Medium, and High**

### 2️⃣ Regression Model

* Predicts **recommended salary hike percentage**
* Helps HR teams design **data-driven compensation strategies**

### 3️⃣ SHAP Explainability

* Identifies **top features influencing predictions**
* Provides **global and local explanations**
* Improves **model transparency and interpretability**

### 4️⃣ Streamlit Dashboard

* Interactive **HR interface**
* Allows users to input employee details
* Visualizes **predictions, insights, and feature importance**

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Random Forest Algorithm**
* **SHAP (Explainable AI)**
* **Matplotlib**
* **Streamlit**

---

## 🧠 Machine Learning Models

### 🔹 Random Forest Classifier

Used to **predict employee attrition**.

**Key Parameters:**

* `n_estimators = 200`
* `criterion = "gini"`
* `max_features = "sqrt"`
* `bootstrap = True`
* `random_state = 42`

---

### 🔹 Random Forest Regressor

Used to **recommend salary hike percentage** based on employee features.

This helps HR teams design **better retention strategies**.

---

## 📊 Evaluation Metrics

The classification model was evaluated using:

* **Accuracy**
* **Precision**
* **Recall**
* **F1 Score**
* **Confusion Matrix**

⚠️ **Recall was prioritized** to ensure that **high-risk employees are not missed**.

---

## 📈 SHAP Explainability

**SHAP (SHapley Additive Explanations)** was used to:

* Identify **top global attrition factors**
* Explain **individual employee predictions**
* Show how each feature **increases or decreases attrition probability**

This ensures **transparency and trust** in HR decision-making.

---

## 🔍 Key Insights

* **Overtime significantly increases attrition risk**
* **Low job satisfaction strongly influences employee exit**
* **Stock option level impacts retention decisions**
* **Salary hike recommendations can reduce attrition probability**
* **SHAP analysis provides personalized retention insights**

---

## 🏗️ System Architecture

```
Raw Data
   ↓
Data Preprocessing
   ↓
Feature Encoding
   ↓
Train-Test Split
   ↓
Random Forest Classification (Attrition Prediction)
   ↓
Risk Score Generation
   ↓
Regression Model (Salary Hike Recommendation)
   ↓
SHAP Explainability
   ↓
Streamlit Dashboard
```

---

## 📌 Future Scope

* Integration with **real-time HR management systems**
* Use of advanced models such as **XGBoost or Deep Learning**
* **Employee sentiment analysis** using NLP
* **Cloud deployment** for enterprise scalability
* Automated **retention strategy recommendations**

---

## 📜 License

This project is developed for **educational and research purposes**.

---

# ⭐ Final Note

This project demonstrates how **Machine Learning and Explainable AI can transform HR decision-making** by combining **predictive accuracy with interpretability**, enabling organizations to make **smarter employee retention strategies**.

---
