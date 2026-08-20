# 🏦 Loan Approval Prediction Using Machine Learning

<p align="center">
  <b>Predicting Loan Approval using Machine Learning</b>
</p>

<p align="center">
  A complete end-to-end machine learning project covering data preprocessing,
  exploratory data analysis, visualization, model training, evaluation and prediction.
</p>

---

## 📌 Project Overview

Loan approval is an important decision-making process in the banking and financial sector.

This project uses Machine Learning to predict whether a loan application is likely to be approved or rejected based on applicant and loan-related information.

The project follows a complete Machine Learning workflow:

Data Collection → Data Cleaning → EDA → Visualization → Preprocessing → 
Model Training → Model Comparison → Evaluation → Prediction

---

## 🎯 Objectives

The main objectives of this project are:

- Understand and explore the loan dataset
- Identify and handle missing values
- Perform exploratory data analysis
- Visualize important patterns and relationships
- Prepare data for Machine Learning
- Encode categorical variables
- Scale numerical variables
- Train multiple classification models
- Compare model performance
- Evaluate the selected model
- Predict loan approval for new applicants

---

## 📂 Dataset

The dataset contains:

- **598 records**
- **13 columns**

### Features

| Feature | Description |
|---|---|
| Loan_ID | Unique loan application ID |
| Gender | Applicant gender |
| Married | Marital status |
| Dependents | Number of dependents |
| Education | Education level |
| Self_Employed | Employment status |
| ApplicantIncome | Applicant income |
| CoapplicantIncome | Co-applicant income |
| LoanAmount | Requested loan amount |
| Loan_Amount_Term | Loan repayment term |
| Credit_History | Credit history |
| Property_Area | Property area |
| Loan_Status | Loan approval status |

### Target Variable

`Loan_Status`

- `Y` → Loan Approved
- `N` → Loan Rejected

This makes the project a **Supervised Binary Classification** problem.

---

## 🔍 Machine Learning Problem

### Learning Type
**Supervised Learning**

The model learns from historical loan applications where the actual loan status is already known.

### Problem Type
**Binary Classification**

The model predicts one of two classes:

- Approved
- Rejected

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab


---

## 🔄 Project Workflow

Dataset
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
Missing Value Analysis
   ↓
Feature Engineering
   ↓
Exploratory Data Analysis
   ↓
Data Visualization
   ↓
Train-Test Split
   ↓
Preprocessing Pipeline
   ↓
Model Training
   ↓
Model Comparison
   ↓
Model Evaluation
   ↓
Feature Interpretation
   ↓
New Applicant Prediction
   ↓
Save Final Model

**MODELS USED**
Logistic Regression – A simple and interpretable classification model.

Decision Tree – Makes predictions using decision-based rules.

Random Forest – Combines multiple decision trees for better performance.

Gradient Boosting – Builds models sequentially to improve prediction errors.

##  Final Result

Four Machine Learning models were trained and compared:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

After comparing the model performance, **Logistic Regression was selected as the final model** for this project.

### Final Model

**Logistic Regression**

The model was used to predict whether a loan application would be:

- ✅ Approved
- ❌ Not Approved

### Evaluation

The Logistic Regression model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

### 📌 Conclusion

Logistic Regression was selected because it provides a simple, interpretable, and effective solution for this binary classification problem. The trained model can be used to predict loan approval for new applicants.
