# Financial-Fraud-Detection

# Dataset Documentation

## Dataset Name
Credit Card Fraud Detection Dataset by Machine Learning Group.

Source
Origin: Machine Learning Group - ULB
URL: Kaggle - Credit Card Fraud Detection
Dataset Description
The dataset contains transactions made by European credit cardholders in September 2013. It includes a mix of fraudulent and non-fraudulent transactions.

Total Records: 284,807
Fraudulent Transactions: 492 (0.172% of total)
Non-Fraudulent Transactions: 284,315
Features
The dataset consists of numerical features that are results of a PCA transformation to ensure privacy.
V1, V2, ..., V28: Principal components derived from PCA.
Time: Seconds elapsed between the transaction and the first transaction in the dataset.
Amount: Transaction amount (helps with cost-sensitivity analysis).
Class: Target variable (1 = Fraudulent, 0 = Non-Fraudulent).
Dataset Characteristics
Attribute	Type	Description
Time	Continuous	Seconds since the first transaction in the dataset.
Amount	Continuous	Transaction amount (in Euros).
V1 to V28	Continuous	Features derived from PCA transformation.
Class	Categorical	Target variable (0 = Non-Fraudulent, 1 = Fraudulent).
Key Points
Class Imbalance: The dataset is highly imbalanced, with less than 0.2% of the transactions being fraudulent. This requires careful handling, such as oversampling or cost-sensitive modeling.
Privacy Protection: Features are anonymized using PCA, which means no domain-specific feature interpretation is possible.