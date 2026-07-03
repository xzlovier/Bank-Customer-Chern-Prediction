# 🏦 Bank Customer Churn Prediction

An end-to-end Machine Learning project that predicts whether a bank customer is likely to churn based on demographic and behavioral features. The project focuses on data preprocessing, exploratory analysis, handling class imbalance, model comparison, and hyperparameter optimization to build a reliable classification model.
---

## 📌 Project Overview

Customer churn is a major challenge for banks, as retaining existing customers is significantly more cost-effective than acquiring new ones. This project develops supervised machine learning models to identify customers at risk of leaving, enabling proactive retention strategies.

---

## 🎯 Objectives

- Predict whether a customer will churn.
- Perform comprehensive data preprocessing.
- Compare multiple classification algorithms.
- Handle class imbalance using SMOTE.
- Optimize model performance through hyperparameter tuning.
- Evaluate model performance using standard classification metrics.

---

## 📂 Dataset

**Dataset:** Bank Customer Churn Dataset

The dataset contains customer demographic, financial, and behavioral information such as:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Credit Card Ownership
- Active Member Status
- Estimated Salary

**Target Variable**

- `Exited`
    - 1 → Customer Churned
    - 0 → Customer Retained

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Imbalanced-learn (SMOTE)

---

## 📊 Project Workflow

### 1. Data Preprocessing

- Missing value handling
- Categorical encoding
- Feature scaling
- Train-test split

---

### 2. Exploratory Data Analysis (EDA)

- Distribution analysis
- Correlation analysis
- Class distribution visualization
- Confusion matrices

---

### 3. Handling Class Imbalance

Applied **SMOTE (Synthetic Minority Oversampling Technique)** to generate synthetic samples for the minority class and improve model learning.

---

### 4. Models Implemented

- Random Forest Classifier
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)

---

### 5. Model Optimization

Hyperparameter tuning performed using **GridSearchCV** to identify the best-performing model configuration.

---

### 6. Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Cross Validation

---

## 📈 Results

- Compared the performance of Random Forest, Decision Tree, and KNN classifiers.
- Improved model generalization using SMOTE and hyperparameter tuning.
- Achieved **up to 86% classification accuracy** on the test dataset.

---

## 📁 Repository Structure

```
├── churn.csv               # Dataset
├── mainp.ipynb             # Jupyter Notebook
├── README.md               # Project Documentation
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/bank-customer-churn-prediction.git
```

2. Navigate to the project folder

```bash
cd bank-customer-churn-prediction
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

If a `requirements.txt` file is not available, install:

```bash
pip install pandas numpy matplotlib scikit-learn imbalanced-learn
```

4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
mainp.ipynb
```

and run all cells.

---

## 📌 Future Improvements

- Implement XGBoost and LightGBM
- Perform feature importance analysis using SHAP
- Build an interactive Power BI or Streamlit dashboard
- Deploy the model using Flask or FastAPI
- Add ROC-AUC and Precision-Recall curve analysis

---

## 📚 Key Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Handling Imbalanced Data
- Supervised Machine Learning
- Hyperparameter Tuning
- Model Evaluation
- Classification Algorithms
- Python Data Science Stack

---
