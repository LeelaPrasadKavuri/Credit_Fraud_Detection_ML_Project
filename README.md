## <p style="color:red"> Credit_Fraud_Detection_ML_Project </p>

>* Data Set is available on Kaggle .  <a target="_blank" rel="noopener" href="https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?datasetId=310&sortBy=voteCount">click_here </a> to View data set in Kaggle.

###  <p style="color:red"> About Credit Cards :-</p>
>* Credit cards are a prevalent means of payment worldwide, with almost three billion cards in circulation. 
>* Financial institutions benefit from credit cards in multiple ways, including interest on unpaid balances, merchant fees, and revenue generated from rewards programs. 
>* Additionally, banks use credit cards to establish relationships with customers, which may lead to the use of other financial services. It's fascinating to note that the Diners Club card was the first credit card, introduced in 1950 for use mainly in restaurants. 
>* Presently, the credit card industry is valued at over $3 trillion and is projected to grow even further, with some experts predicting global credit card transactions to hit $45 trillion by 2023.
>* Another remarkable fact about credit cards is that they have revolutionized the way people shop and make purchases. With the advent of contactless payments and mobile wallets, credit cards have become even more convenient and accessible. 
>* Moreover, credit cards have enabled individuals to build credit, which is crucial for securing loans, mortgages, and other financial products. 
>* Overall, credit cards have become an indispensable tool for individuals and financial institutions alike.

### Goal of Project :- 
>* It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase

### Description About Dataset:-
>* The dataset contains transactions made by credit cards in September 2013 by European cardholders.
>* This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
>* It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, author didn't provided the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. 
>* Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
>* Given the class imbalance ratio, author recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.

