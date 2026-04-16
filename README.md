# Lloyds-Banking-customer-churn-analysis-
Customer churn prediction using Python and machine learning 
# Customer Churn Prediction Analysis

## Project Overview
This project focuses on analyzing customer behavior and building a predictive model to identify customers likely to churn. The goal is to help businesses take proactive actions to improve customer retention.

---

## Dataset
The dataset consists of multiple sources:
- Customer demographics
- Transaction history
- Customer service interactions
- Online activity data

These datasets were merged using CustomerID to create a comprehensive view of customer behavior.

---

## Exploratory Data Analysis (EDA)
Key techniques used:
- Histograms for distribution analysis
- Boxplots for detecting outliers
- Scatter plots for relationships

###  Key Insights:
- Customers with low spending are more likely to churn
- Low login frequency strongly indicates churn
- Unresolved complaints increase churn risk

---

##  Data Preprocessing
- Handled missing values using imputation and logical assumptions
- Created new features:
  - TotalSpending
  - NumTransactions
  - NumComplaints
  - DaysSinceLastLogin
- Encoded categorical variables using one-hot encoding
- Converted date features into meaningful numeric values

---

## Model Building
- Model: Logistic Regression
- Data split: 80% training, 20% testing

---

## Results
The model successfully predicts customer churn and highlights key drivers such as:
- Customer activity
- Spending behavior
- Service interactions

---

## Business Impact
Businesses can use this model to:
- Identify at-risk customers
- Send personalized offers
- Improve customer retention strategies

---

## Tools & Libraries
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

---

## Conclusion
This project demonstrates the importance of data preprocessing and feature engineering in building effective machine learning models.

---

## Author
Abdulbasit Folawiyo Dimeji
