# Loan Approval Prediction using Logistic Regression  

##  Project Overview  
This project applies a **Logistic Regression** model to predict **loan approval status** based on applicant details such as income, credit history, employment, and demographic attributes.  
The model was trained on a **synthetic credit risk dataset of 45,000 records** and achieved an accuracy of **89.01%** on the test set.  

---

##  Methodology  

### 1. EDA & Preprocessing  
- Performed exploratory data analysis (EDA) to understand feature distributions and correlations.  
- Encoded categorical variables (e.g., gender, education, home ownership).  
- Scaled numerical features (e.g., income, loan amount, credit score).  

### 2. Model Training  
- Used **Logistic Regression Classifier**.  
- Dataset split into **80% training** and **20% testing**.  

### 3. Evaluation Metrics  
- Accuracy Score  
- Classification Report  
- Confusion Matrix  

---

## Results  

- **Accuracy:** `89.01%`  
- **F1-Score (Not Approved):** `0.93`  
- **F1-Score (Approved):** `0.75`  

The model shows strong performance in identifying loan rejections (Not Approved) while maintaining good predictive power for approvals.  

---

## How to Run  

### Dependencies  
Install the required Python libraries:  

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
