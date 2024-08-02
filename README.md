# Customer-Churn-Prediction-
Customer Churn Prediction for Telecom Industry

Introduction
Customer churn, the phenomenon of customers ceasing to use a company's services, is a significant concern for businesses, especially in the telecommunications sector. High churn rates directly impact revenue and growth. This project aims to develop a predictive model to identify customers likely to churn, enabling proactive retention strategies.

** Dataset **
The analysis utilizes the "Telco Customer Churn" dataset obtained from Kaggle:

Source: https://www.kaggle.com/datasets/blastchar/telco-customer-churn   
Features: The dataset contains 7,043 customer records with 21 features, including demographics (gender, age, etc.), services utilized (phone, internet, etc.), account information (tenure, contract type, monthly charges), and the target variable 'Churn' (Yes/No).


** Data Cleaning & Preparation **
Converted 'TotalCharges' column to numeric format.
Filled missing 'TotalCharges' values with the median.
Removed the 'customerID' column as it's not relevant for prediction.
Methodology


** Exploratory Data Analysis (EDA) ** :
Analyzed the distribution of churn (class imbalance noted).
Visualized churn rates across different customer segments (e.g., gender, senior citizen status).
Examined relationships between tenure, monthly charges, and churn.



** Created new features to enhance model performance:** 
TenureMonths: Converted tenure from months to a continuous variable.
HasPhoneService: Binary indicator for phone service.
One-hot encoded categorical variables.
Model Building:

Built two models:
Logistic Regression: A simple, interpretable linear model.
Random Forest: A robust ensemble model known for handling non-linear relationships.
Model Evaluation:

Used train-test split to evaluate model generalization.
Employed classification report (precision, recall, F1-score) and confusion matrix.
Results


Insights & Recommendations
Customers with shorter tenure and higher monthly charges are more prone to churn.
Fiber optic internet service is associated with higher churn.
Month-to-month contracts exhibit the highest churn rates.
Recommendations:

Offer personalized incentives to customers with high churn risk.
Design loyalty programs for long-term customers.
Review pricing and bundling strategies for fiber optic service.
Explore options to convert month-to-month customers to longer-term contracts.
How to Run
Environment:
Ensure you have Python installed.
Install required libraries using pip install pandas scikit-learn matplotlib seaborn.
Execution:
Open the churn_prediction.ipynb Jupyter Notebook.
Run cells sequentially to replicate the analysis.

Author
Kazi Adit Hossain

LinkedIn: [Your LinkedIn Profile Link]
