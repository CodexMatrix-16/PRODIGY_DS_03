# Prodigy InfoTech Data Science Internship Task 3:

# Decision Tree Classifier – Bank Marketing Dataset

# Overview
 
-  This project builds a Decision Tree Classifier to predict whether a customer will purchase a product/service (term deposit) based on their demographic and behavioral data.
The dataset comes from the Bank Marketing Dataset (UCI Machine Learning Repository) which contains information from direct marketing campaigns carried out by a Portuguese banking institution.

# Dataset
 
-  Target Variable: y → Whether the client subscribed to a term deposit.
-  Features include:
   -  Job, Marital status, Education
   -  Housing and Personal Loan status
   -  Contact communication type
   -  Month of last contact
   -  Campaign-related attributes
   -  Age, Balance, etc.

# Data Preprocessing & Observations

-  Categorical variables encoded for ML modeling.
-  Missing values handled where necessary.
-  Notable insights:
   -  Most clients are married and working as admin.
   -  Most chose cellular as the contact method.
   -  Majority contacted in July.
   -  Dataset is imbalanced (majority did not subscribe).

# Model Development

-  Implemented Decision Tree Classifier using:
   -  Gini Criterion
   -  Entropy Criterion
-  Compared performance of both approaches.

# Conclusion

-  High Accuracy For Criteria: Both Gini and Entropy provide high accuracy which is 90.1% for Gini and 90.2% for Entropy but we don't consider accuracy is our primary metric because our dataset is imbalanced.

-  Performance Metrics Comparison: 1]The Entropy criterion has a slightly better recall for the positive class (1), indicating it is better at identifying true positive instances. 2]The Gini criterion results in fewer false positives but more false negatives compared to Entropy.

