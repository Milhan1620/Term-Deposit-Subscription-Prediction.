# 💰 Term Deposit Subscription Prediction

## 📌 Project Overview
This project predicts whether a bank customer will subscribe to a term deposit after a marketing campaign using machine learning classification algorithms. The goal is to help banks identify potential customers and improve marketing efficiency.

---

## 🎯 Objective
Build a predictive classification model that determines whether a customer will subscribe to a term deposit based on demographic information, financial status, and previous campaign interactions.

---

## 📂 Dataset
**Bank Marketing Dataset**

Source: UCI Machine Learning Repository

The dataset contains customer demographic details, banking information, and previous marketing campaign outcomes.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SHAP / LIME

---

## 📊 Workflow

### 1. Data Loading
- Load dataset
- Inspect structure
- Handle missing values

### 2. Exploratory Data Analysis (EDA)
- Dataset overview
- Class distribution
- Correlation analysis
- Feature visualization

### 3. Data Preprocessing
- Encode categorical variables
- Feature scaling
- Train-test split

### 4. Model Training
Implemented classification models:
- Logistic Regression
- Random Forest Classifier

### 5. Model Evaluation
Performance evaluated using:
- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1 Score
- ROC Curve
- ROC-AUC Score

### 6. Explainable AI (XAI)
Model predictions are explained using:
- SHAP
- LIME

At least five predictions are interpreted to understand feature contributions.

---

## 📈 Results
The project compares multiple classification models and selects the best-performing model based on evaluation metrics.

---

## 📚 Skills Demonstrated

- Classification Modeling
- Feature Encoding
- Machine Learning Evaluation
- Explainable AI (SHAP/LIME)
- Customer Behavior Analysis

---

## 📁 Project Structure

```
├── data/
├── notebook.ipynb
├── requirements.txt
├── README.md
└── images/
```

---

## 🚀 Future Improvements

- Hyperparameter tuning
- Cross-validation
- XGBoost and LightGBM implementation
- Model deployment with Streamlit
