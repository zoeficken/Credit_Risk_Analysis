# Credit_Risk_Analysis

## Overview of the Analysis

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then, I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Lastly, I evaluated the performance of these models.

## Results

Naive Random Oversampling 

<img width="767" alt="Screen Shot 2021-12-12 at 5 37 45 PM" src="https://user-images.githubusercontent.com/88108455/145732346-c24ea2c7-10f1-4c1e-b7b7-b4deb0bfc325.png">

- Balanced Accuracy Score: 0.6497536370265621
- Precision Score: The precision is low for High-risk loans and is high for Low-risk loans
- Recall Score: 0.62 High Risk/ 0.68 Low Risk

SMOTE Oversampling

<img width="750" alt="Screen Shot 2021-12-12 at 5 39 47 PM" src="https://user-images.githubusercontent.com/88108455/145732420-d0de98cc-3e95-42ca-a0ec-8b2599f30280.png">

- Balanced Accuracy Score: 0.6443721269403855
- Precision Score: The precision is low for High-risk loans and is high for Low-risk loans
- Recall Score: 0.63 High Risk/ 0.66 Low Risk

Undersampling

<img width="669" alt="Screen Shot 2021-12-12 at 5 41 59 PM" src="https://user-images.githubusercontent.com/88108455/145732489-56742eb3-316f-45ba-9279-cd4bb72b7a42.png">

- Balanced Accuracy Score: 0.6443721269403855
- Precision Score: The precision is low for High-risk loans and is high for Low-risk loans
- Recall Score: 0.61 High Risk/ 0.45 Low Risk

Combination Sampling 

<img width="743" alt="Screen Shot 2021-12-12 at 5 43 19 PM" src="https://user-images.githubusercontent.com/88108455/145732517-6bd67d38-e51a-4eb9-9e99-fa32ca642da9.png">

- Balanced Accuracy Score: 0.5292150629907619
- Precision Score: The precision is low for High-risk loans and is high for Low-risk loans
- Recall Score: 0.70 High Risk/ 0.57 Low Risk

Balanced Random Forest

<img width="680" alt="Screen Shot 2021-12-12 at 5 48 00 PM" src="https://user-images.githubusercontent.com/88108455/145732654-997386e7-7fd0-4251-a7de-12908513a8cd.png">

- Balanced Accuracy Score: 0.7877672625306695
- Precision Score: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall Score: 0.67 High Risk/ 0.91 Low Risk

Easy Ensemble

<img width="681" alt="Screen Shot 2021-12-12 at 5 48 57 PM" src="https://user-images.githubusercontent.com/88108455/145732685-3080a8b6-7812-4588-a029-641a7b911e0c.png">

Balanced Accuracy Score: 0.9229904850855175
Precision Score: The precision is low for High-risk loans and is high for Low-risk loans.
Recall Score: 0.67 High Risk/ 0.91 Low Risk

## Summary

For the credit card risk data set, all of the classifiers tested showed similar recall scores, and all had precision scores as low for high-risk loans and high for low-risk loans. The Easy Ensemble Classifier is the best choice when analyzing credit risk because the accuracy score was the highest at 0.92.

