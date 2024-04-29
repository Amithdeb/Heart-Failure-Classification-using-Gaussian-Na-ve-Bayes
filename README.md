# Heart-Failure-Classification-using-Gaussian-Na-ve-Bayes
Here, Naive Bayes algorithm is applied to the given dataset of heart_fail_clinical_records_datasets.
As, from the co-relation heat-map, there is a strong co-relation between sex and smoking. 
so, we remove the feature 'sex' as in naive biase algorithm, every features should be independent.
From the analysis of the histogram plot of every features, the optimal NB variant that is found is GaussianNB. 
In this type, we get the accuracy of 73% which is highest possible. After that, we used the MultinomialNB, BernouliNB, CategorigalNB, ComplementNB. Accuracy is quite good in the case of CategoricalNB. 
But Accuracy is quite low in the case of MultinomialNB, BernouliNB, ComplementNB.
