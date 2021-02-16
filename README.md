# Credit Card Fraud Detection by Machine Learning

It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

The datasets contains transactions made by credit cards in September 2013 by european cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions. the dataset is taken from the <a href="https://www.kaggle.com/mlg-ulb/creditcardfraud"> kaggle site. </a>

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues,the original features are not provided and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

The details of the modeling for this imbalaced dataset is provided in this <a href="https://github.com/Mithunprom/Credit-Card-Fraud-Detection-by-Machine-Learning/blob/main/Credit_card_fraud_detection.ipynb"> jupyter file </a>. The imbalanced dataset is taken care by undersampling the dominant class to the size of rare class. Descriptive analysis of the dataset is also provided in this project. For the ease of visualization, I used the T-SNE for the Feature Extraction. Finally I used cross-validation to spot check different modeling algorithm for this dataset.


