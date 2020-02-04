# Fraud-Detection

Dataset Link : https://drive.google.com/file/d/1AVGlE3M8eDqfqMpybhFPkUNwtw9PSM03/view?usp=sharing

Goals:  
1) Create a 50/50 sub-dataframe ratio of "Fraud" and "Non-Fraud" transactions. (NearMiss Algorithm)      
2) Determine the Classifiers we are going to use and decide which one has a higher accuracy.
3) Create a Neural Network and compare the accuracy to our best classifier.

Conclusion:
SMOTE on imbalanced dataset helped our model to classify more Fraud transactions.Undersample data our model is unable to detect for a large number of cases non fraud transactions correctly and instead, misclassifies those non fraud transactions as fraud cases.

Note:
Carefull while applying SMOTE, it must be applied on training set only.
Accurcay may change, since both type of datasets were subjected to shuffling. 
