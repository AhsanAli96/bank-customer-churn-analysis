# bank-customer-churn-analysis
Customer churn analysis and prediction using Python and Machine Learning
# Bank Customer Churn Analysis & Prediction

## Project Overview

This project analyzes bank customer data to understand the factors that influence customer churn. The goal is to identify patterns in customer behavior and build a machine learning model that can predict whether a customer will leave the bank.

Customer churn is an important business problem because retaining existing customers is often more cost-effective than acquiring new ones.

---

## Dataset

The dataset contains information about 10,000 bank customers and includes the following features:

* CreditScore
* Geography
* Gender
* Age
* Tenure
* Balance
* NumOfProducts
* HasCrCard
* IsActiveMember
* EstimatedSalary
* Exited (Target Variable)

**Target Variable**

* 0 → Customer stays with the bank
* 1 → Customer leaves the bank (Churn)

---

## Project Workflow

### 1. Data Loading

The dataset was loaded using the Pandas library and inspected to understand its structure.

### 2. Exploratory Data Analysis (EDA)

Several analyses were performed to understand customer behavior:

* Churn distribution analysis
* Age vs Churn analysis
* Balance vs Churn analysis
* Correlation heatmap to identify relationships between features

### 3. Data Preprocessing

Data preprocessing steps included:

* Encoding categorical variables
* Converting Gender and Geography to numeric values
* Feature scaling using StandardScaler

### 4. Machine Learning Model

A Logistic Regression model was used to predict customer churn.

The dataset was split into:

* 80% training data
* 20% testing data

### 5. Model Evaluation

The model performance was evaluated using accuracy and confusion matrix.

**Model Accuracy:**
Approximately **81%**

---

## Key Insights

* Around **20% of customers left the bank**.
* **Age has the strongest positive correlation with churn**, meaning older customers are more likely to leave.
* Customers from **Germany showed a higher churn rate** compared to other regions.
* **Active members are less likely to churn**.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Future Improvements

* Apply advanced machine learning models such as Random Forest or XGBoost
* Perform hyperparameter tuning
* Deploy the model as a web application

---

## Author

Muhammad Ahsan Ali
Aspiring Data Analyst | Python | Machine Learning | Data Visualization

