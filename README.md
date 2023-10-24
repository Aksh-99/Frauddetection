# Frauddetection
This repository contains analysis of the PaySim synthetic financial dataset, which is a synthetic dataset that simulates mobile money transactions. The dataset is based on a sample of real transactions extracted from one month of financial logs from a mobile money service implemented in an African country. The original dataset can be found on Kaggle: [PaySim1](https://www.kaggle.com/datasets/ealaxi/paysim1).

## Dataset Description

The dataset contains the following columns:

1. `step` - maps a unit of time in the real world. In this case, 1 step is 1 hour of time. Total steps are 744 (30 days simulation).
2. `type` - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.
3. `amount` - amount of the transaction in local currency.
4. `nameOrig` - customer who started the transaction.
5. `oldbalanceOrg` - initial balance before the transaction.
6. `newbalanceOrig` - new balance after the transaction.
7. `nameDest` - customer who is the recipient of the transaction.
8. `oldbalanceDest` - initial recipient balance before the transaction.
9. `newbalanceDest` - new recipient balance after the transaction.
10. `isFraud` - identifies a fraudulent transaction (1) and non fraudulent (0).
11. `isFlaggedFraud` - flags illegal attempts to transfer more than 200,000 in a single transaction.

## Analysis Objective

The main objective of this analysis is to understand the patterns and trends in the data, and to identify fraudulent transactions.






