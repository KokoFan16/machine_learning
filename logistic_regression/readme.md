## Logistic Regression 

This project asks you to implement a logistic regression classifier with Newton's method by your own (without sklearn’s LogisticRegression), and apply it on a real data set.

## Dataset

We use the Breast Cancer Wisconsin dataset from UCI machine learning repository: http://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

## Newton's method
Please read Slides 44 – 50 on https://www.cs.cmu.edu/~mgormley/courses/10701-f16/slides/lecture5.pdf to learn Newton’s method.

## Requirement

- Please randomly sample 80% of the training instances to train a classifier and then testing it on the remaining 20%.
- Ten such random data splits should be performed and the average over these 10 trials is used to estimate the generalization performance.
- Please use sklearn’s LogisticRegression to verify if you get the same accuracy.
