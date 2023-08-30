# Ensemble-Classifiers-and-K-Means-Clustering
CSE-6363-001-MACHINE LEARNING under Manfred Huber: Ensemble Classifiers and K-Means Clustering

**Ensemble Classifiers:**
1. Revisiting material prediction:
a) Implement a bagging routine for a softmax regression classifier. You can use your own implementation from Project 1 or reference an existing one.
b) Apply bagging 10, 50, and 100 times to the training data. Evaluate ensemble classifiers on the test dataset and compare error rates against a single classifier. Discuss the results obtained.

2. Employ boosting on the data and softmax regression classifier:
a) Implement AdaBoost on top of your softmax regression classifier. Modify your own version from Project 1 or adapt an existing implementation for weighted sample sets.
b) Apply boosting 10, 25, and 50 times to the training data. Evaluate ensemble classifiers on the test dataset and compare error rates against a single classifier. Briefly discuss the results.

**K-Means Clustering:**
3. Consider the dataset from Problem 2c in the first assignment without labels:
a) Implement K-Means Clustering for this problem.
b) Apply K-Means clustering with K values of 3, 6, and 9. Assess cluster alignment with the original labels. Compute accuracy for each cluster by assuming the most frequent label in a cluster as its predicted label. Calculate the overall accuracy as the weighted sum of cluster accuracies based on the fraction of data points in each cluster.

In summary, we explore ensemble classifiers through bagging and boosting, evaluate their performance, and then proceed to K-Means clustering with various cluster counts to assess cluster-label alignment.
