# **Loan Approval Prediction 🏦**

This project focuses on predicting loan approval status using machine learning techniques. The workflow covers **data preprocessing, feature engineering, handling class imbalance, and model training/evaluation**, all implemented with a mix of automation through custom functions.

---

## **📂 Project Overview**

The goal of this project is to predict whether a loan application will be approved based on applicant details (numerical & categorical features). The process demonstrates **practical ML pipeline building**, from raw dataset to model evaluation.

---

## **🔑 Key Steps**

### **1\. Data Exploration & Cleaning**

* Loaded dataset from Kaggle.

* Checked for **missing values** (`NaN`) and handled them.

* **Outlier detection** performed using boxplots.

* Applied **capping** technique to handle outliers.

### 

### 

### 

### **2\. Data Visualization**

* Boxplots → to spot outliers.

* Histplots → to visualize feature distributions.

* Correlation heatmap → to study relationships among features.

### **3\. Feature Engineering**

* Checked skewness → applied **log transformation** on skewed features.

* Dropped **low correlation features**.

* **Standardized numerical features**.

* **Encoded categorical variables** using Label Encoding & One-Hot Encoding.

### **4\. Handling Class Imbalance**

* Checked class distribution.

* Applied **SMOTE (Synthetic Minority Oversampling Technique)** to balance classes.

### **5\. Model Training & Evaluation**

* Split dataset into training & testing sets.

* Trained **Logistic Regression** model.

* Evaluated with:

  * **Classification Report** (Precision, Recall, F1-score).

  * **Confusion Matrix**.

* After SMOTE, retrained model → **slightly better results**.

---

## **⚙️ Automation with Custom Functions**

Instead of rewriting code repeatedly, custom functions were created that made the workflow **reusable and efficient**.

---

## **📊 Results**

* **Logistic Regression (before SMOTE):** Baseline performance.

* **Logistic Regression (after SMOTE):** Improved recall & F1-score for minority class.

---

## **🚀 Tech Stack**

* **Python**

* **Pandas, NumPy** → Data wrangling

* **Matplotlib, Seaborn** → Visualization

* **Scikit-learn** → Preprocessing & ML

* **Imbalanced-learn** → SMOTE

---

## **📌 Future Improvements**

* Experiment with more powerful models (Random Forest, XGBoost).

* Hyperparameter tuning.

* Build an end-to-end deployment (e.g., Streamlit app).

