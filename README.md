 Loan Status Prediction using Machine Learning

# Overview
This project predicts whether a loan will be approved, paid, or defaulted using Machine Learning techniques. It helps financial institutions make data-driven decisions and reduce financial risk.

The model analyzes borrower details such as age, loan amount, education, and repayment behavior to classify loan status.

---

# Objectives
- Predict loan status using ML models  
- Reduce financial risk in lending  
- Automate loan decision-making process  
- Understand key factors affecting loan repayment  

---

# Dataset
The dataset contains 500 records and 11 features:

- Loan_ID  
- loan_status (Target)  
- Principal (Loan Amount)  
- terms  
- effective_date  
- due_date  
- paid_off_time  
- past_due_days  
- age  
- education  
- Gender  

---

# Tech Stack
- Language: Python  
- Tools: Jupyter Notebook  
- Libraries:
  - Pandas  
  - NumPy  
  - Matplotlib  
  - Seaborn  
  - Scikit-learn  

---

# Project Workflow

# Data Preprocessing
- Removed unnecessary columns (Loan_ID)  
- Handled missing values  
- Converted date columns into datetime format  
- Encoded categorical variables  

# Feature Engineering
- Extracted:
  - effective_day  
  - due_day  
  - paid_day  
- Created:
  - loan_duration  

# Data Visualization
- Count plots  
- Histograms  
- Box plots  
- Scatter plots  
- Correlation heatmap  

# Model Building
- Algorithm: Logistic Regression  
- Train-Test Split: 80-20  
- Feature Scaling: StandardScaler  

# Model Evaluation
- Accuracy Score  
- Confusion Matrix  

---

# Results
- Achieved accuracy of ~70%–85%  
- Important features:
  - Loan Duration  
  - Past Due Days  
  - Principal Amount  

---

# Visualizations
The project includes:
- Loan Status Distribution  
- Age Distribution  
- Loan Amount Distribution  
- Correlation Heatmap  
- Feature Importance Graph
