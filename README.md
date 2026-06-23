# Loan Default Prediction System

##  Project Overview

The **Loan Default Prediction System** is a Machine Learning-based project that predicts whether a borrower is likely to default on a loan or not.

This system helps banks and financial institutions reduce risk by analyzing customer details such as income, credit history, loan amount, employment status, and other financial factors to make better lending decisions.

---

##  Problem Statement

Loan defaults cause financial losses for banks and lenders. Traditional methods of checking loan eligibility may not always accurately identify risky customers.

This project aims to build a predictive model that can classify borrowers as:

-  Low Risk (Loan will be repaid)
-  High Risk (Possible Loan Default)

---

##  Features

- User-friendly loan prediction interface
- Customer financial data analysis
- Machine Learning-based prediction
- Risk classification
- Fast prediction results
- Data preprocessing and model training

---

##  Technologies Used

### Programming Language
- Python

### Machine Learning
- Scikit-learn
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Seaborn

### Frontend (Optional)
- HTML
- CSS
- JavaScript
- Streamlit

### Database (Optional)
- MySQL / Firebase

---

##  Project Structure
Loan-Default-Prediction-System/

│
├── dataset/
│ └── loan_data.csv
│
├── model/
│ └── loan_prediction_model.pkl
│
├── notebooks/
│ └── model_training.ipynb
│
├── app.py
├── requirements.txt
├── README.md
└── screenshots/


---

##  Dataset Features

The dataset contains information like:

| Feature | Description |
|---|---|
| Age | Customer age |
| Income | Monthly/Annual income |
| Loan Amount | Requested loan amount |
| Credit Score | Credit history score |
| Employment Status | Job details |
| Loan Term | Loan duration |
| Debt Ratio | Existing financial obligations |
| Default | Target variable |

---

##  Machine Learning Workflow

### 1. Data Collection
Collect historical loan data containing customer information.

### 2. Data Preprocessing

- Handling missing values
- Removing duplicate data
- Encoding categorical variables
- Feature scaling

### 3. Exploratory Data Analysis

Analyze patterns using:

- Data visualization
- Correlation analysis
- Statistical analysis

### 4. Model Training

Machine Learning algorithms used:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine

### 5. Model Evaluation

Performance measured using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

##  Model Prediction

Input Example:


Age: 35
Income: 50000
Loan Amount: 200000
Credit Score: 720
Employment: Salaried


Output:


Prediction: Low Risk
Loan Approval Probability: 85%


---

##  How to Run the Project

### Step 1: Clone Repository


git clone https://github.com/yourusername/loan-default-prediction.git


### Step 2: Install Dependencies


pip install -r requirements.txt


### Step 3: Run Application


python app.py


---

##  Requirements


pandas
numpy
scikit-learn
matplotlib
seaborn
streamlit


---

##  Future Improvements

- Add Deep Learning model
- Real-time banking API integration
- Improve prediction accuracy
- Add customer dashboard
- Deploy using cloud services

---

## 👨‍💻 Author

** S.Tharun sasi **

---

##  Conclusion

The Loan Default Prediction System helps financial organizations identify risky borrowers using Machine Learning techniques, i
