# Linear Models

Linear model specifies a linear combination of features. The training process learns one weight for each feature. The higher the weight value is, the more important the feature is.

## Multiclass Classification

* [Predict tags from the titles of StackOverflow posts](https://github.com/msfchen/machine_learning/tree/master/linearmodel/tagprediction): features: bag-of-words vs tf-idf; 100 classes; classifier: OneVsRestClassifier(LogisticRegression()); evaluation: F1-Score Macro, F1-Score Weighted, ROC-AUC [2/28/2018, Coursera Advanced ML Specialization]