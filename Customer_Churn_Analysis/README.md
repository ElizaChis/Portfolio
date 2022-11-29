### Customer Churn Analysis

We want to predict the outflow of customers for the telecom operator. If the user plans to leave, he/she will be offered promotional codes and special conditions. We compare different models by AUC ROC and aim to choose a stable model.

We studied historical data on customer behavior, removed missing values and changed the data type of some parameters and added some features (time). Next, we have noticed that we have a class imbalance and did upsampling after we divided the data into sets. We considered 4 models: Logistic Regression, Decision Tree, KNN, RandomForestClassifier and catboost. For some models, it was necessary to use upsampling and data encoding. We compared different models in terms of AUC ROC, also looked at precision, recall & F1 score. We looked at different parameters and decided that catboost_grid has a very good result. This result was also tested on a test sample.

**KEYWORDS**: python, data cleaning, upsmapling, encoding, Logistic Regression, Decision Trees, KNN, RandomForestClassifier, Catboost
