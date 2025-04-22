# Big-Data-Project

The problem to be addressed is the design and implementation of a robust, real-time fraud detection system capable of:
- Accurately identifying fraudulent transactions in a highly imbalanced dataset.
- Processing streaming data with low latency and high throughput to handle exponential transaction volumes and detect fraud as it occurs.

This problem requires an integrated solution combining distributed data streaming technologies with machine learning models, in order to achieve both scalability and precision in a real-world financial environment.


## Datset
The data description for the Financial Fraud Detection Dataset on Kaggle is detailed below:
Total Rows: 500,000 transactions

Columns: 11

Key Columns Include:


step:  timestamp or sequence step of the transaction

type: Type of transaction (e.g., CASH_OUT, TRANSFER)

amount: Transaction amount

oldbalanceOrg & newbalanceOrig: Sender’s balance before and after

oldbalanceDest & newbalanceDest: Receiver’s balance before and after

isFraud: Label indicating if the transaction is fraudulent

isFlaggedFraud: Whether the transaction was flagged manually

You can explore or download it here: [Financial Fraud Detection Dataset – Kaggle](https://www.kaggle.com/datasets/sriharshaeedala/financial-fraud-detection-dataset)

