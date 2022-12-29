# credit_card_fraud_detection
It is the responsibility of the credit card companies to ensure that their customers are given the best security measures when it comes to fraudulent
credit card transactions. The main objective of this
work is to explore whether a credit card transaction
(before being processed) is fraudulent or not. And if it
is found out to be fraudulent, then the credit card
owner must be notified of the same. The approach used
is to make use of highly imbalanced and skewed
transactional data and train various models available
in ML as well as a DL model for the detection of frauds
and finally compare their accuracies and test results
and choose the most suitable model. The system
currently used to detect fraud is plagued by
misclassifications and highly false positives. So, our
motive is to not miss any fraud cases (high recall) as
well as not predict too many non-fraud cases as fraud
cases (high precision) as if this happens, it will lead to
poor reviews for the concerned credit card company.
We demonstrate various methods to deal with the
imbalance of the data such as choosing appropriate
metrics for evaluation of models and resampling of
data.

The fraud detection module will work in the following steps:
1. The Incoming set of transactions and amount are treated as credit card
transactions.
2. The credit card transactions are given to machine learning algorithms as
an input.
3. The output will result in either fraud or valid transaction by analyzing the
data and observing a pattern using the best chosen model.
4. The fraud transactions are given an alarm which alerts the user that a
fraud transaction has occurred and the user can block the card to prevent
further financial loss to him as well as the credit card company.
5. The valid transactions are treated as genuine transactions.
