# Credit_Risk_Analysis

# Purpose of the analysis
Credit risk creates a vastly unbalanced classification issue due to the incredibly large amount of data points that can be used when identifying the risk level. The purpose of this repository is to create a trustworthy process of evaluating credit through the use of machine learning algorithms. I used a combination of machine learning tools that can be found in the imbalanced-learn and scikit-learn libraries to write evaulation models using resampling and classifiers to reduce bias. 

The data set that I used to create these algorithms is from LendingClub which is a peer-to-peer lending services company. 

# Results 

- ## RandomOverSampler

![RandomOverSampler](https://user-images.githubusercontent.com/84791455/137640517-9e2a53ab-94ab-4186-83a7-64f9d9f92429.PNG)

- ## SMOTE

![SMOTE](https://user-images.githubusercontent.com/84791455/137640561-5fbaba77-e85b-41c5-a148-861924209287.PNG)

- ## ClusterCentroids

![ClusterCentroids](https://user-images.githubusercontent.com/84791455/137640579-8370f252-bf83-43c1-bb07-2850fc9462c1.PNG)

- ## SMOTEENN

![SMOTEENN](https://user-images.githubusercontent.com/84791455/137640605-fbe47270-c7d7-4c35-a775-4dd1d54dff3c.PNG)

- ## BalancedRandomForestClassifier

![BalancedRandomForestClassifier](https://user-images.githubusercontent.com/84791455/137640645-b1ba8f72-c195-4d45-a6be-955e888ce371.PNG)

- ## EasyEnsembleClassifier

![EasyEnsembleClassifier](https://user-images.githubusercontent.com/84791455/137640683-b4e9293c-38e2-4bb5-810f-9651f6a94012.PNG)


# Summary
- The results are relatively consistent with the oversampling and undersampling models. However, with these models, the highest accuracy was only just abover 65%. The highest f1 score was only 80% which is ok but it can be better. When I ran the two classifier models to help reduce bias, I saw a vast improvement in accuracy and f1 scores, both models averaged over 90% accuracy score and above .9 f1 scores. 

- I would recommend using the EasyEnsembleClassifier because it had the best overall scores when testing the model. This is likely the model that will yield the most correct predictions when analyzing credit risk. 
