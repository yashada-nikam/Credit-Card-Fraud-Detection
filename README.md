# Credit-Card-Fraud-Detection


This project focuses on the prediction of fraudulent credit card transactions using machine learning models. The ability to accurately identify and classify fraudulent transactions is crucial for credit card companies to protect their customers from unauthorized charges and minimize financial losses.

The [dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) used in this project contains transactions made by European credit cardholders over a two-day period in September 2013. The dataset is highly imbalanced, with the positive class representing fraudulent transactions accounting for only a small percentage of all transactions. The challenge lies in developing robust machine learning models that can effectively handle this class imbalance and accurately predict fraudulent transactions.

**Objective**

The primary objective of this project is to build a predictive model that can accurately classify credit card transactions as fraudulent or non-fraudulent. By doing so, we aim to help credit card companies identify and take appropriate actions against fraudulent activities, thereby reducing the financial impact on both the customers and the companies.

**Approach**

The project follows a data science workflow to develop and evaluate the predictive models. The key steps involved in the project are as follows:

Exploratory Data Analysis (EDA): Perform exploratory analysis to gain insights into the dataset, understand the distribution of fraudulent and non-fraudulent transactions, and identify any patterns or dependencies.

Data Preprocessing: Handle missing values, address outliers (if any), and perform feature scaling or transformation as required. Split the data into training and testing sets while maintaining the class imbalance.

Model Development: Train and evaluate various machine learning models suitable for imbalanced classification, with a focus on logistic regression. Explore different techniques to handle class imbalance, such as undersampling, oversampling, or SMOTE.

Model Evaluation: Assess the performance of the trained models using appropriate evaluation metrics for imbalanced classification, such as precision, recall, F1 score, and area under the ROC curve (AUC-ROC). Adjust the decision threshold if necessary to achieve the desired trade-off between precision and recall.

**Conclusion**

In the case of banks with smaller average transaction values, it is crucial to prioritize high precision. This is because it is essential to accurately identify relevant transactions as fraudulent. To ensure precision, additional steps can be taken, such as involving human verification by contacting the customer for each flagged transaction. However, when precision is low, such tasks become burdensome as they require an increased human element.

For banks dealing with larger transaction values, low recall becomes a concern as it implies a failure to detect transactions labeled as non-fraudulent. In such cases, the potential losses incurred from missing a high-value fraudulent transaction need to be considered.

Therefore, to protect banks from high-value fraudulent transactions, the focus should be on achieving a high recall to effectively detect actual instances of fraud.

Therefore, opting for the logistic model seems appropriate in this scenario. Furthermore, this model is comparatively easier to interpret and explain to the business stakeholders.
