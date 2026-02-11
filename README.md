# loan_prediction-credit risk analysis
Loan approval prediction using Python, Pandas, Seaborn, and scikit‑learn. Includes data preprocessing, EDA, model training, and evaluation.
# Loan approval Prediction-credit risk analysis Project

## 📌 Overview
This project predicts loan approval status using machine learning.  
It demonstrates end-to-end data science workflow: data cleaning, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

## 📊 Dataset
The dataset contains information about loan applicants with the following columns:

- Loan_ID  
- Gender  
- Married  
- Dependents  
- Education  
- Self_Employed  
- ApplicantIncome  
- CoapplicantIncome  
- LoanAmount  
- Loan_Amount_Term  
- Credit_History  
- Property_Area  
- Loan_Status  

Target variable: **Loan_Status** (`Y` = Approved, `N` = Not Approved)

## ⚙️ Steps
1. **Data Preprocessing**
   - Handled missing values
   - Encoded categorical variables using one-hot encoding
   - Mapped target variable (`Y` → 1, `N` → 0)

2. **Exploratory Data Analysis (EDA)**
   - Count plots for loan status
   - Box plots for income vs. loan status
   - Correlation heatmap for numeric features

3. **Model Training**
   - Train-test split (80/20)
   - RandomForestClassifier used as baseline model

4. **Evaluation**
   - Classification report (accuracy, precision, recall, F1-score)
   - Feature importance analysis

## 📈 Results
- RandomForest achieved **XX% accuracy** on test data (replace with your actual score).
- Key features influencing loan approval include **Credit_History, ApplicantIncome, LoanAmount, Property_Area**.

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- scikit-learn  

## 🚀 Future Improvements
- Hyperparameter tuning with GridSearchCV  
- Model comparison (Logistic Regression, Decision Tree, XGBoost)  
- Feature scaling for numeric variables  
- Cross-validation for more reliable performance estimates  

## 📂 Repository Structure
