# Overview of Project
Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.
# DELIVERABLE RESULTS:
Below are the results from the various techniques used to predictive model for High-Risk loans.
![image](https://user-images.githubusercontent.com/90371048/149712556-f71a64f8-188e-4461-ac7c-86ac6adf62fb.png)
![image](https://user-images.githubusercontent.com/90371048/149713080-d1fd0224-8fb3-49bd-99d2-4dddfa44ab86.png)


# SUMMARY
For all models, utlizing EasyEnsembleClassifier is the most effective. Provides a highest Score for all Risk loans. The precision is low or none for all the models. In General, above the 90% of the current analysis, utlizing EasyEnsembleClassifier will perform a High-Risk loan precision as a great value for the overall analysis.

