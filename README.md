# Sales-Prediction
A machine learning project to detect fraudulent credit card transactions. Includes data preprocessing, class imbalance handling (SMOTE), and classification using Logistic Regression and Random Forest with precision, recall, and F1-score evaluation.
Credit Card Fraud Detection
# 📌 Overview
This project focuses on building a machine learning model to detect fraudulent credit card transactions. The dataset is highly imbalanced, so techniques like SMOTE are applied to handle class imbalance. Models such as Logistic Regression and Random Forest are trained and evaluated using metrics like precision, recall, F1-score, and ROC-AUC.

# 📊 Dataset
The dataset creditcard.csv contains:

Time – Seconds elapsed between the transaction and the first transaction.

V1 to V28 – Anonymized PCA features.

Amount – Transaction amount.

Class – Target variable (0 = Genuine, 1 = Fraud).

# 🚀 Project Workflow
Data Exploration & Cleaning – Check class distribution and data quality.

Data Preprocessing – Normalize columns like Time and Amount.

Handling Class Imbalance – Apply SMOTE (Synthetic Minority Oversampling Technique).

Model Training – Train Logistic Regression and Random Forest models.

Model Evaluation – Use precision, recall, F1-score, and ROC-AUC to evaluate results.

Visualization – Confusion matrix and class distribution plots.

# 🧠 Key Insights
Fraudulent transactions are extremely rare compared to genuine ones.

SMOTE significantly improves the model’s ability to detect fraud cases.

Random Forest delivers better recall compared to Logistic Regression.

# 🛠️ Tools & Libraries
Python

Pandas, NumPy – Data manipulation

Matplotlib, Seaborn – Visualization

Scikit-learn – Model building and evaluation

Imbalanced-learn – SMOTE for handling imbalanced datasets

# 📈 Results
Improved detection of fraud cases by balancing the dataset.

Achieved high precision and recall using Random Forest with proper tuning.
