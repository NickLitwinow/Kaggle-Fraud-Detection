![nb](https://user-images.githubusercontent.com/44932745/210684564-8a09ea8d-4733-433e-ac7b-a3cbed60a6b3.png)


# IEEE Fraud Detection EDA

This project provides an exploratory data analysis (EDA) for the IEEE Fraud Detection dataset available on Kaggle. The analysis focuses on understanding the structure and characteristics of the transaction and identity data provided for both training and testing.

## Project Overview

The objective of this project is to perform an in-depth EDA on the IEEE Fraud Detection data. The analysis includes:
- **Data Reading:** Importing transaction and identity data from CSV files.
- **Visualization:** Creating time histograms, regular histograms, and correlation plots to visualize the distribution of values over time and understand the relationships between features.
- **Descriptive Statistics:** Generating detailed descriptive statistics for both the entire datasets and key segments (e.g., fraudulent vs. non-fraudulent transactions, public vs. private test data).
- **Correlation Analysis:** Identifying the most correlated features with key variables such as `TransactionDT` and `isFraud`.

## Dataset Description

The dataset consists of four CSV files:
- **train_transaction.csv:** Transaction data for training.
- **test_transaction.csv:** Transaction data for testing.
- **train_identity.csv:** Identity data for training.
- **test_identity.csv:** Identity data for testing.

Key columns include:
- **TransactionDT:** The transaction timestamp.
- **TransactionAmt:** The amount involved in the transaction.
- **isFraud:** The target variable indicating whether a transaction is fraudulent.
- Other features (both numeric and categorical) that describe the transactions and the identities of the cardholders.
