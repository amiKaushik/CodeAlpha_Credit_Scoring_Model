# 🏦 Credit Scoring Model – Predicting Creditworthiness

## 📌 Project Overview

This project focuses on predicting an individual's **creditworthiness** using past financial data. By applying **classification algorithms** such as Logistic Regression and Random Forest, the model determines whether a client is likely to be a **good** or **bad** credit risk.

The dataset used is the **German Credit Data (numeric version)**.

---

## 🎯 Objectives

* Predict **creditworthiness** based on financial history.
* Apply **classification algorithms** (Logistic Regression, Decision Tree, Random Forest).
* Assess model performance using **Precision, Recall, F1-Score, ROC-AUC**.
* Provide **visual insights** into model performance and feature importance.

---

## 📊 Dataset

* **Source:** German Credit Data (numeric version) [Link](https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data)
* **Features:**

  * Income, debts, payment history
  * Credit history, savings, employment duration
  * Housing, age, number of dependents
* **Target Variable:**

  * `1` = Good Credit Risk
  * `0` = Bad Credit Risk

---

## ⚙️ Approach

1. **Data Preprocessing**

   * Feature engineering & scaling with `StandardScaler`
   * Target mapping (`1=Good`, `2=Bad → 0=Bad`)

2. **Model Training**

   * Logistic Regression
   * Random Forest Classifier

3. **Evaluation Metrics**

   * Confusion Matrix
   * Classification Report (Precision, Recall, F1-Score)
   * ROC Curve & ROC-AUC Score

4. **Model Explainability**

   * Feature importance (Random Forest)
   * ROC comparison plots

---

## 📈 Results

* **Logistic Regression**

  * Interpretable but lower ROC-AUC compared to ensemble methods.
* **Random Forest**

  * Better at capturing non-linear relationships.
  * Provided higher **ROC-AUC** and **feature importance insights**.

---

## 🔧 Tech Stack

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib
* **ML Models:** Logistic Regression, Random Forest

---

## 📂 Repository Structure

```
├── Credit_Scoring_Model.ipynb   # Jupyter Notebook with implementation
├── requirements.txt
├── README.md                    # Project documentation
```

---

## 🚀 How to Run

1. Clone this repo:

   ```bash
   git clone https://github.com/amiKaushik/Credit-Scoring-Model.git
   cd Credit-Scoring-Model
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook:

   ```bash
   jupyter notebook Credit_Scoring_Model.ipynb
   ```

---

## 📌 Future Improvements

* Hyperparameter tuning (GridSearchCV, RandomizedSearchCV).
* Try advanced models (XGBoost, LightGBM).
* Address class imbalance with **SMOTE** or other techniques.
* Deploy as a **web app** for credit scoring predictions.

---

## 📬 Contact

👤 **Your Name**
🔗 [LinkedIn](https://www.linkedin.com/in/kaushik-das-919928317) | [GitHub](https://github.com/amiKaushik)
