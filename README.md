# customer-churn-prediction-lloyds
## Project Overview
--

Customer churn is a major challenge for financial institutions. Losing customers directly impacts revenue and long-term growth.

In this project, I developed a machine learning pipeline to analyze customer behaviour and predict churn risk using demographic, transactional, and engagement data.

The goal was to identify patterns that indicate when a customer may leave the bank and provide insights that can support proactive retention strategies.

--
## Dataset

The dataset consisted of multiple tables representing different aspects of customer behavior:

Customer demographics

Transaction history

Customer service interactions

Online activity

Churn status

These datasets were merged into a unified customer-level dataset to support predictive modelling.

--
## Exploratory Data Analysis

EDA was conducted to identify patterns between customer behaviour and churn. Key areas explored included:

Customer age distribution

Transaction activity

Customer service interactions

Online engagement levels

Initial findings suggested that lower engagement and transaction activity may signal increased churn risk.

--
## Machine Learning Model

A Random Forest classifier was used to predict customer churn.

The dataset was split into:

80% training data

20% testing data

Model performance was evaluated using:

Accuracy

Precision

Recall

F1 Score

Confusion Matrix

--
## Key Insights

Feature importance analysis showed that the most influential variables included:

Login frequency

Transaction count

Customer service interactions

Customers with declining engagement were significantly more likely to churn.

--
## Technologies Used

Python

Pandas

Scikit-learn

Matplotlib

Seaborn
