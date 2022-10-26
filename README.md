# Overview of the analysis
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, different techniques need to be emplyed to train and evaluate models with unbalanced classes. 

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, data is oversampled using the RandomOverSampler and SMOTE algorithms, and undersampled using the ClusterCentroids algorithm. Then, a combinatorial approach of over- and undersampling using the SMOTEENN algorithm was used. Next, two new machine learning models that reduce bias are compared, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 

## Deliverables

* Deliverable 1: Use Resampling Models to Predict Credit Risk
* Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
* Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
* Deliverable 4: A Written Report on the Credit Risk Analysis (README.md)


## Results
### Deliverable 1 (Oversampling and Under Sampling)
* An accuracy score for the model is calculated to 0.99
* A confusion matrix has been generated 
![1](https://user-images.githubusercontent.com/105166481/197945927-22819439-4761-4cce-9375-159cf9108916.png)
![Naive_Oversampling](https://user-images.githubusercontent.com/105166481/197945974-c32eb30b-8f05-469e-83b9-9826b172b578.png)![SMOTE_Oversampling](https://user-images.githubusercontent.com/105166481/197945981-03a1f018-cd3a-4456-8c80-6e2f80cc9373.png)


* An imbalanced classification report has been generated 
![2](https://user-images.githubusercontent.com/105166481/197945937-aece3294-e6a8-487a-b032-90c1e8d03a9c.png)

### Deliverable 2 (SMOTEENN -  Combination of Over and Under Sampling)

* An accuracy score for the model is calculated to be 0.82
* A confusion matrix has been generated 
![Smotten plot](https://user-images.githubusercontent.com/105166481/197946008-a5afcee9-acfa-4ab2-b28e-8ceeeb713f56.png)

* An imbalanced classification report has been generated 
![Smotten report](https://user-images.githubusercontent.com/105166481/197946051-00c05650-3a12-465f-b46d-fbe7db73d9b4.png)


### Deliverable 3 

#### The BalancedRandomForestClassifier algorithm does the following:

* An accuracy score for the model is calculated 
* A confusion matrix has been generated 
* An imbalanced classification report has been generated 
* The features are sorted in descending order by feature importance 
##### The EasyEnsembleClassifier algorithm does the following:
* An accuracy score of the model is calculated 
* A confusion matrix has been generated 
* An imbalanced classification report has been generated 


## Summary
* Compared to all models EasyEnsemble model gave the best accuarcy while balanced accuracy has the least accuracy.
* Hence I recommend EasyEnsemble model.

