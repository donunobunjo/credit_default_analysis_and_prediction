📌 Credit Default Analysis and Prediction
📖 Project Overview
This project analyzes and predicts loan default risk using the Credit Dataset.

Goals:

🔎 Identify key financial and demographic risk factors for credit default
🤖 Build predictive models to classify applicants as low risk or high risk
📊 Provide insights to support better lending decisions
GitHub
🎯 Objectives
Perform Exploratory Data Analysis (EDA)
Clean & preprocess the dataset (missing values, duplicates, encoding)
Engineer features (loan-to-income ratio, age groups, etc.)
Train and evaluate multiple machine learning models
Visualize and interpret the results
🛠️ Tech Stack
🐍 Python
📊 Pandas / NumPy → Data wrangling
🎨 Matplotlib / Seaborn → Visualization
🤖 Scikit-learn → ML models & metrics
📓 Jupyter Notebook → Analysis & reporting
📊 Dataset
Name: Credit Dataset
Source: Credit Dataset
🔍 Exploratory Data Analysis (EDA)
Questions explored:

👤 Does age influence default risk?
💰 Are low savings/checking balances linked to higher default?
🏠 Does housing status (own, rent, free) affect repayment?
📈 How does loan amount vs. income affect creditworthiness?
📌 Visualizations:

Distribution plots (age, loan amount, duration)
Default rate by housing, employment, credit history
Correlation heatmap
🤖 Machine Learning Approach
Models tested:

Logistic Regression (baseline)
Decision Tree
Random Forest
Metrics used:

✅ Accuracy
🎯 Precision, Recall, F1-score
📈 AUC-ROC Curve
✅ Results & Insights
Housing Status : Owning a house correlates with better credit performane.

Purpose : Those applicants whose credit purposes are for Furniture/Appliances and new cars show lower risk. While those for used cars and education show very high rkis.

Employement duration : Having stable job generally correlates with better credit performance.

Savings Balance : Low savings balance and unknown savings balance seems to show the lowest default rates

Age Matters : Young applicants (within the ages of 25 and 40) are associated with the highest default rates, while applicants less than 25 years show lower risk

Model Comparison Summary
Model	Accuracy	AUC
Random Forest	0.765	0.7972
Logistic Regre	0.750	0.7692
Decision Tree	0.685	0.7153
57		
