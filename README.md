# Credit_Risk_Analysis

The purpose of this analysis is to apply supervised machine learning alogthrims to determine credit card risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Using the credit card credit dataset from LendingClub, this project oversamples the data using the RandomOverSampler and SMOTE algorithms, and undersamples the data using the ClusterCentroids algorithm. Also, using a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Lastly, compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

## 6 different methods were used:

### 1. Naive Random Oversampling
<img width="743" alt="Screen Shot 2021-12-27 at 9 09 57 PM" src="https://user-images.githubusercontent.com/89141436/147520011-767e3fa2-016c-4bde-a6ef-ccf4f7bd42cd.png">

### 2. SMOTE Oversampling
<img width="743" alt="Screen Shot 2021-12-27 at 9 12 31 PM" src="https://user-images.githubusercontent.com/89141436/147520164-fbffb1ca-b9e7-4b14-8e36-87f25547fd18.png">

### 3. Cluster Centroid Undersampling
<img width="743" alt="Screen Shot 2021-12-27 at 9 13 05 PM" src="https://user-images.githubusercontent.com/89141436/147520195-d9fc00eb-6c65-4593-9c09-19f7e4e5d757.png">

### 4. SMOTEENN Sampling
<img width="743" alt="Screen Shot 2021-12-27 at 9 13 48 PM" src="https://user-images.githubusercontent.com/89141436/147520253-024f40bc-c482-4bf0-b1de-c700a68c1957.png">

### 5. Balanced Random Forest Classifying
<img width="743" alt="Screen Shot 2021-12-27 at 9 14 28 PM" src="https://user-images.githubusercontent.com/89141436/147520288-877f135d-6856-4610-8b71-ce547a118cc8.png">

### 6. Easy Ensemble Classifying
<img width="743" alt="Screen Shot 2021-12-27 at 9 15 06 PM" src="https://user-images.githubusercontent.com/89141436/147520331-20f08025-8dfe-4d14-b0fe-2fccabbfad21.png">
