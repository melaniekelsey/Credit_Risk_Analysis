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
The first model I used was the Random Oversampler model. The balanced accuracy score, as seen in the image below is about 65%. The high risk precision is about 1% and the sensitivity (or recall) is about 62%. With those 2 stats, the F1 score is 2% for the high risk population, a very low number, which means there is a pronounced imbalance between precision and sensivity. 

![RandomOverSampler.png](https://github.com/melaniekelsey/Credit_Risk_Analysis/blob/main/images/RandomOverSampler.png)

### SMOTE Oversampler
The second model I used was the SMOTE Oversampler model. The balanced accuracy score was the same as the Random Oversampler at 65%, with the same high risk precision and sensitvity numbers/ 
![SMOTEOversampler.png](https://github.com/melaniekelsey/Credit_Risk_Analysis/blob/main/images/SMOTEOversampler.png)

### Cluster Centroids
![ClusterCentroids.png](https://github.com/melaniekelsey/Credit_Risk_Analysis/blob/main/images/ClusterCentroids.png)

### SMOTEENN
![SMOTEENN.png](https://github.com/melaniekelsey/Credit_Risk_Analysis/blob/main/images/SMOTEENN.png)

### Balanced Random Forest Classifier
![BalancedRandomForestClassifier.png](https://github.com/melaniekelsey/Credit_Risk_Analysis/blob/main/images/BalancedRandomForestClassifier.png)

### Easy Ensemble Classifier
![EasyEnsembleClassifier.png](https://github.com/melaniekelsey/Credit_Risk_Analysis/blob/main/images/EasyEnsembleClassifier.png)
## Summary

Overall, I believe that there in not bias towards unpaid or paid reviewers. As you can see, the paid reviewers tend to give less reviews overall than the upaid reviewers. if anything, maybe they are more critical and less likely to give 5 stars than the unpaid reviewers. The comparison of 68.9% unpaid reviewers to the 28.5% paid reviewers is staggering. Maybe the paid reviewers rate so many products that they are more discerning of their 5 stars? While, the unpaid reviewers are giving their unbiased opinions? 

I think a further deep dive would be to look at the actual different product categories. I selected Pet Supplies, but there might be better datasets that hit a bigger audience than just pet owners to really fully determine if there is bias. If could be, that pet owners are more likely to vote a review as helpful as opposed to the a more general category. 
