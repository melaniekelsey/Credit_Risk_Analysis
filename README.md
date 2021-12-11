# Credit_Risk_Analysis

## Overview of the Analysis

I was asked to create various Supervised Machine Learning Models to predict credit risk. I used 6 different methods to evaluate the risk.
  - Random Oversampler
  - SMOTE
  - Cluster Centroids
  - SMOTEENN
  - Balanced Random Forest Classifier
  - Easy Ensemble Classifier

## Results

### Random Oversampler
![RandomOverSampler.png](https://github.com/melaniekelsey/Credit_Risk_Analysis/blob/main/images/RandomOverSampler.png)

### SMOTE Oversampler
![SMOTEOversampler.png](https://github.com/melaniekelsey/Credit_Risk_Analysis/blob/main/images/SMOTEOversampler.png)

### Cluster Centroids
![ClusterCentroids.png](https://github.com/melaniekelsey/Credit_Risk_Analysis/blob/main/images/ClusterCentroids.png)

### SMOTEENN
![SMOTEENN.png](https://github.com/melaniekelsey/Credit_Risk_Analysis/blob/main/images/SMOTEENN.png)

![BalancedRandomForestClassifier.png](https://github.com/melaniekelsey/Credit_Risk_Analysis/blob/main/images/BalancedRandomForestClassifier.png)

![EasyEnsembleClassifier.png](https://github.com/melaniekelsey/Credit_Risk_Analysis/blob/main/images/EasyEnsembleClassifier.png)
## Summary

Overall, I believe that there in not bias towards unpaid or paid reviewers. As you can see, the paid reviewers tend to give less reviews overall than the upaid reviewers. if anything, maybe they are more critical and less likely to give 5 stars than the unpaid reviewers. The comparison of 68.9% unpaid reviewers to the 28.5% paid reviewers is staggering. Maybe the paid reviewers rate so many products that they are more discerning of their 5 stars? While, the unpaid reviewers are giving their unbiased opinions? 

I think a further deep dive would be to look at the actual different product categories. I selected Pet Supplies, but there might be better datasets that hit a bigger audience than just pet owners to really fully determine if there is bias. If could be, that pet owners are more likely to vote a review as helpful as opposed to the a more general category. 
