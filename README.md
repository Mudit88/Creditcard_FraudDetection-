# Creditcard_FraudDetection
The Project is to recognize fraudulent credit card transactions so that the customers of credit card companies are not charged for items that they did not purchase.

![image](https://github.com/Mudit88/Creditcard_FraudDetection-/assets/88089351/713ca215-5885-48a9-97f4-7b18a704abc1)


#Main challenges involved in credit card fraud detection are:

1) Enormous Data is processed every day and the model build must be fast enough to respond to the scam in time.
2) Imbalanced Data i.e most of the transactions (99.8%) are not fraudulent which makes it really hard for detecting the fraudulent ones
3) Data availability as the data is mostly private.
4) Misclassified Data can be another major issue, as not every fraudulent transaction is caught and reported.
5) Adaptive techniques used against the model by the scammers.

#How to tackle these challenges?

1) The model used must be simple and fast enough to detect the anomaly and classify it as a fraudulent transaction as quickly as possible.
2) Imbalance can be dealt with by properly using some methods which we will talk about in the next paragraph
3) For protecting the privacy of the user the dimensionality of the data can be reduced.
4) A more trustworthy source must be taken that double-checks the data, at least for training the model.
5) We can make the model simple and interpretable so that when the scammer adapts to it with just some tweaks we can have a new model up and running to deploy.
