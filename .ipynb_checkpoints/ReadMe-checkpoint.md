# 📌 Credit Default Analysis and Prediction  

## 📖 Project Overview  
This project analyzes and predicts **loan default risk** using the German Credit Dataset.  

**Goals:**  
- 🔎 Identify key financial and demographic risk factors for credit default  
- 🤖 Build predictive models to classify applicants as *low risk* or *high risk*  
- 📊 Provide insights to support better lending decisions  

---

## 🎯 Objectives  
1. Perform **Exploratory Data Analysis (EDA)**  
2. Clean & preprocess the dataset (missing values, duplicates, encoding)  
3. Engineer features (loan-to-income ratio, age groups, etc.)  
4. Train and evaluate multiple machine learning models  
5. Visualize and interpret the results  

---

## 🛠️ Tech Stack  
- 🐍 Python  
- 📊 Pandas / NumPy → Data wrangling  
- 🎨 Matplotlib / Seaborn → Visualization  
- 🤖 Scikit-learn → ML models & metrics  
- ⚡ XGBoost / LightGBM → Advanced boosting  
- 📓 Jupyter Notebook → Analysis & reporting  

---

## 📊 Dataset  
- **Name:** German Credit Dataset  
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data)  

| Property  | Details |  
|-----------|---------|  
| Records   | 1,000 applicants |  
| Features  | 20 (categorical + numerical) |  
| Target    | `default` (1 = bad credit, 0 = good credit) |  

---

## 🔍 Exploratory Data Analysis (EDA)  
Questions explored:  
- 👤 Does **age** influence default risk?  
- 💰 Are low **savings/checking balances** linked to higher default?  
- 🏠 Does **housing status** (own, rent, free) affect repayment?  
- 📈 How does **loan amount vs. income** affect creditworthiness?  

📌 Visualizations:  
- Distribution plots (age, loan amount, duration)  
- Default rate by housing, employment, credit history  
- Correlation heatmap  
- Feature importance plots  

---

## 🤖 Machine Learning Approach  
**Models tested:**  
- Logistic Regression (baseline)  
- Decision Tree  
- Random Forest  
- Gradient Boosting (XGBoost / LightGBM)  

**Metrics used:**  
- ✅ Accuracy  
- 🎯 Precision, Recall, F1-score  
- 📈 AUC-ROC Curve  

---

## ✅ Results & Insights  
- Applicants with **low checking balance**, **short employment duration**, and **high loan amount** are at higher risk.  
- Boosting models outperform traditional models.  

📊 Best model performance:  
| Metric     | Score |  
|------------|-------|  
| Accuracy   | XX%   |  
| F1-Score   | XX%   |  
| AUC-ROC    | XX%   |  

*(replace XX% with your actual results)*  

---

## 🚀 How to Run This Project  

```bash
# 1. Clone repo
git clone https://github.com/your-username/credit-default-analysis.git  

# 2. Navigate into project folder
cd credit-default-analysis  

# 3. Install dependencies
pip install -r requirements.txt  

# 4. Launch Jupyter Notebook
jupyter notebook
