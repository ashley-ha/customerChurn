## Customer Churn Prediction 
Author: Ashley Eastman
Date: Feberuary 20th, 2023

### Overview
This project focuses on predicting customer churn for a cellphone company using machine learning techniques. The dataset contains information about customers and whether they stayed or left the company. The goal is to build a predictive model that can help identify customers who are likely to churn, allowing the company to take proactive measures to retain them.

### Dataset
The dataset consists of 7032 entries and 7 columns, including information such as monthly charges, senior citizen status, payment method, internet service type, tenure, and contract type. Data cleaning has been performed prior to the analysis.

### Exploratory Data Analysis (EDA)
EDA was conducted to gain insights into the data. Key findings include:

- Monthly charges are not a strong indicator of customer churn.
- Senior citizens have a higher churn rate compared to other customers (41%).
- Tenure has a negative correlation with churn, suggesting that longer tenure reduces the likelihood of churn.

### Modeling
Two models were applied for customer churn prediction:

- Logistic Regression: After feature selection and optimization of the threshold value, the model achieved an accuracy of approximately 76.54%.
- Linear Discriminant Analysis (LDA): LDA was also used to predict churn, resulting in an accuracy of about 78.58%.
Feature Importance
- The most significant feature for predicting churn was whether the customer is a senior citizen. Other influential factors included the type of internet service and payment method.

### Conclusion
This project successfully built predictive models to identify customer churn. It revealed that senior citizens and specific internet service types are more likely to churn. By taking proactive actions based on the predictions, the company can reduce customer churn and improve overall retention rates.

### Recommendations
For future improvements, it is recommended to gather more customer data, such as the platform used (app, web) or specific services utilized. This additional data could enhance the accuracy and understanding of churn factors, leading to more effective retention strategies.

For more details and code implementation, please refer to the provided code and analysis in the project files.

For further inquiries, kindly contact Ashley Eastman at ashleyha@berkeley.edu.
