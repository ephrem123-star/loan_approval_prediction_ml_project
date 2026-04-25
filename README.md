# Loan Approval Prediction using Machine Learning

## Problem Statement
Financial institutions need reliable ways to evaluate loan applications.
This project aims to automate loan approval decisions using machine learning models trained on historical data.

## Dataset
Source: Loan Approval Dataset  
Records: 4269  

Features:
* Income  
* Loan Amount  
* Loan Term  
* CIBIL Score  
* Assets (residential, commercial, etc.)  
* Education Status  
* Employment Status  

## Approach

### Data Cleaning
* Removed unnecessary columns (e.g., loan_id)  
* Handled missing values  
* Cleaned categorical variables  

### Exploratory Data Analysis (EDA)
* Analyzed relationships between features and loan approval  
* Identified key patterns (e.g., impact of CIBIL score)  

### Feature Engineering
* Selected relevant features  
* Removed redundant asset columns  

### Data Preprocessing
* Encoding categorical variables  
* Feature scaling using StandardScaler  

### Model Building
* Logistic Regression (baseline)  
* Random Forest  
* XGBoost  

### Model Evaluation
* Accuracy Score  
* Confusion Matrix  
* Classification Report  

## Results
* Logistic Regression: 90.5%  
* Random Forest: 97.6%  
* XGBoost: 98.8%  

XGBoost performed best, achieving high accuracy with minimal prediction errors.

## Key Insights
* CIBIL Score is the most important factor in loan approval  
* Higher income increases approval probability  
* Asset ownership improves chances of approval  
* Financial stability strongly influences decisions  

## Visualizations
* Model comparison chart  
* Confusion matrix  
* Feature importance plot  

## Tech Stack
* Python  
* Pandas  
* NumPy  
* Scikit-learn  
* XGBoost  
* Matplotlib  
* Seaborn  

## Conclusion
This project demonstrates how machine learning can be used to support data-driven decision-making in financial services.
The model helps reduce risk and improve efficiency in loan approval processes.

## Author
Ephrem Ftye  
Aspiring Data Scientist | Machine Learning Enthusiast
