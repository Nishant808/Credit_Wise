# 💳 CreditWise: Loan Approval Prediction System

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

## 📌 Project Overview
**CreditWise** is a machine learning solution designed to automate the evaluation of loan applications. Using historical applicant data, the system predicts whether a loan should be approved based on financial and demographic factors. This project showcases a robust data science workflow, including advanced data cleaning, exploratory data analysis (EDA), and classification modeling.

## 🎯 Key Objectives
* **Data Integrity**: Cleaned a raw dataset of 1,000 records, addressing missing values using statistical imputation.
* **Feature Engineering**: Prepared high-dimensional data (20 features) for optimal model performance.
* **Predictive Modeling**: Implemented a Naive Bayes classifier to achieve reliable risk assessment.

## 📊 Dataset Insights
The project utilizes `loan_approval_data.csv`, which includes features such as:
* **Applicant Profile**: Age, Income, Employment Status, and Education Level.
* **Financial Health**: Credit Score, Debt-to-Income (DTI) Ratio, and Savings.
* **Loan Details**: Loan Amount, Loan Term, and Purpose.
* **Target Variable**: `Loan_Approved` (Binary classification).

## 🛠️ Technical Workflow
1.  **Data Preprocessing**: 
    * Numerical missing values filled using the **Mean** strategy.
    * Categorical missing values filled using the **Most Frequent** strategy.
    * Applied feature scaling to ensure uniform weight distribution across variables.
2.  **Exploratory Data Analysis (EDA)**: Analyzed the distribution of loan approvals and identified key correlations between credit scores and approval rates.
3.  **Model Implementation**: Trained a **Gaussian Naive Bayes** model, chosen for its efficiency in high-dimensional financial datasets.
4.  **Evaluation**: Assessed performance using a Confusion Matrix and standard classification metrics.

## 📈 Performance Results
The model demonstrated strong predictive power on the test set:

| Metric | Score |
| :--- | :--- |
| **Accuracy** | **86%** |
| **Precision** | **81.1%** |
| **Recall** | **70.5%** |
| **F1 Score** | **75.4%** |

**Confusion Matrix Highlights**:
* True Negatives (Correctly rejected): 129
* True Positives (Correctly approved): 43

## 🚀 Getting Started
### Prerequisites
* Python 3.8+
* Jupyter Notebook

### Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/CreditWise.git](https://github.com/yourusername/CreditWise.git)
