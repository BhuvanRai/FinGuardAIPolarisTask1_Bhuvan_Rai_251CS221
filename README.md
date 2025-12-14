Online Payment Fraud Detection
Dataset Introduction

This dataset contains simulated mobile money transactions used to identify fraudulent online payments.
The target variable isFraud indicates whether a transaction is fraudulent (1) or legitimate (0).

🧹 Data Preprocessing

Transactions with amount < 1000 were removed to focus on high-value payments

No missing values were found in the dataset

📊 Exploratory Data Analysis (EDA)

Fraud transactions represent only ~0.13% of all transactions

Fraud is highly imbalanced, requiring metrics beyond accuracy

Fraud occurs mainly in TRANSFER and CASH_OUT transaction types

Transaction type is a strong indicator of fraudulent behavior
