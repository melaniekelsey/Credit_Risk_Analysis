# Credit_Risk_Analysis

## Overview of the Analysis

I was asked to use various Supervised Machine Learning Models to predict credit risk using a dataset from LendingClub, a peer-to-peer lending services company. I used  4 methods over 6 different models to predict credit risk. 

#### Oversampling Methods
  - Random Oversampler
  - SMOTE
#### Undersampling Method
  - Cluster Centroids
#### Combination Over/Undersampling Method
  - SMOTEENN
#### Machine Learning Models
  - Balanced Random Forest Classifier
  - Easy Ensemble Classifier


## Results

### Random Oversampler
The first model I used was the Random Oversampler model. The balanced accuracy score, as seen in the image below is about 65%. The high risk precision is about 1% and the sensitivity (or recall) is about 62%. With those 2 stats, the F1 score is 2% for the high risk population, a very low number, which means there is a pronounced imbalance between precision and sensitivity. 

![RandomOverSampler.png](https://github.com/melaniekelsey/Credit_Risk_Analysis/blob/main/images/RandomOverSampler.png)

### SMOTE Oversampler
The second model I used was the SMOTE Oversampler model. The balanced accuracy score was similar to the Random Oversampler at 64%, with the same high risk precision of 1% and 63% sensitivity. This also had the same F1 score of 2% for the high risk population, showing the pronounced imbalance between precision and sensitivity. 

![SMOTEOversampler.png](https://github.com/melaniekelsey/Credit_Risk_Analysis/blob/main/images/SMOTEOversampler.png)

### Cluster Centroids
The third model I used was Cluster Centroids, an undersampler model. THe balanced accurary score for this model was 53%. The precision was 1% and sensitivity was 61% for high risk population. This model had an even lower F1 score of 1%. 

![ClusterCentroids.png](https://github.com/melaniekelsey/Credit_Risk_Analysis/blob/main/images/ClusterCentroids.png)

### SMOTEENN
The fourth model I used was a combo of undersampling and oversampling with the SMOTEENN model. This model had results similar to the first two models with 64% balanced accuracy, 1% precision, 71% sensitivity and an F1 score of 2%. 

![SMOTEENN.png](https://github.com/melaniekelsey/Credit_Risk_Analysis/blob/main/images/SMOTEENN.png)

### Balanced Random Forest Classifier
The fifth model I used was Balanced Random Forest Classifier. The balanced accurary score was higher than the previous four models, coming in at 79%. The precision was slightly higher at 4%. The sensitivity was 67% and the F1 score was 7%. Slightly higher than the previous four models. 

![BalancedRandomForestClassifier.png](https://github.com/melaniekelsey/Credit_Risk_Analysis/blob/main/images/BalancedRandomForestClassifier.png)

### Easy Ensemble Classifier
The final model I used was Easy Ensemble Classifier. This model had the highest accuracy coming in at 93% . The precision was 7% and the sensitivity was 91%. The F1 score came in at 14%. 

![EasyEnsembleClassifier.png](https://github.com/melaniekelsey/Credit_Risk_Analysis/blob/main/images/EasyEnsembleClassifier.png)

## Summary

Overall, all 6 models had weak precision and weak F1 scores, even the model with the highest balanced accuracy score (Easy Ensemble Classifier) predicted 979 cases where the client would be considered high risk, despite the fact that they were low risk. That is a good amount of potential clients that the lending company could lose. It's important that these companies have decent precision AND decent sensitivity. I believe that none of the models used would be good predictors for credit risk. There's too big of a chance of missing potential clients. More research needs to be done to find a better predictive model than the 6 that I used. 
