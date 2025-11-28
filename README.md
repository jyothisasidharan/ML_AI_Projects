💳 Personal Bank Loan Classifier – Machine Learning Project
📌 Project Overview

The Personal Bank Loan Classifier is a machine learning project designed to predict whether a customer is likely to be approved for a personal loan based on their demographic, financial and behavioral attributes.

This project demonstrates the complete end-to-end ML workflow, including data preprocessing, exploratory data analysis, model building, hyperparameter tuning, evaluation and insights generation.

🛠️ Tech Stack

Python
NumPy, Pandas
Matplotlib, Seaborn
Scikit-learn
XGBoost
Jupyter Notebook

📂 Dataset

The dataset includes features such as:

Age
Income
Credit Score
Work Experience
Mortgage
Family size
Personal loan status
Securities account
CD account
Online banking usage
Education level

🧹 Data Preprocessing

Steps performed:

Handling missing values
Detecting & treating outliers
Encoding categorical variables
Feature scaling (StandardScaler / MinMax)
Feature selection based on importance
Train–test split (80/20)

🔍 Exploratory Data Analysis (EDA)

Visualizations include:
Distribution plots
Correlation heatmap
Loan approval patterns
Income vs. Loan approval
Credit score patterns

Key insights:

Higher income customers showed a higher likelihood of loan approval.
Credit score and experience were strong predictors.
Customers with CD accounts were more likely to be approved.

🤖 Models Implemented

Multiple classification models were trained and compared:

Logistic Regression
KNN
Decision Tree
Random Forest
XGBoost
Support Vector Machine (SVM)
Naive Bayes
DBSCAN

🎯 Hyperparameter Tuning

Performed using GridSearchCV / RandomizedSearchCV:

Number of estimators
Max depth
Learning rate (XGBoost)
K-values for KNN
Kernel selection for SVM

📈 Model Evaluation

Metrics used:

Accuracy
Precision
Recall
F1-Score
ROC–AUC Curve
Confusion Matrix

⭐ Best Model Outcome

The model with the highest performance was:
XGBoost

📊 Feature Importance

Top predictors include:

Income
Credit Score
CD Account
Education Level

Age

(Modify based on your actual outcome)
