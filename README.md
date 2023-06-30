# Purchasing Intention

## Dataset

The dataset consists of feature vectors belonging to **12,330 sessions**.
The dataset was formed so that each session
would belong to a different user in a 1-year period to avoid
any tendency to a specific campaign, special day, user
profile, or period.

Additional informations about the dataset such as how the data collected, can be found on the following URL:
http://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset

## Project Goal

Of the 12,330 sessions in the dataset, 84.5% (10,422) were negative class samples that did not end with shopping, and the rest (1908) were positive class samples ending with shopping. The goal of the project is to predict if a session end with shopping or not.

## Conclusion

I used 3 different Machine Learning model (Logistic Regression, Random Forest Classifier, CatBoost). Accuracy scores for these models are:

* Logistic Regression: 0.8828
* Random Forest Classifier: 0.8930
* CatBoost: 0.8918
