# Kaggle_problems
Solution to some of the Kaggle problems 

How to model Credit card Approval prediction based on the application data & Credit report Data.

1) Learn to construct the bad/good labels. 
2) Learn how to deal with Imbalanced datasets using Ensemble as well as different sampling techniques.
3) Model explainabilty and analysis using feature importances and shap values.


4) Tried ensembling techniques like Bagging, Boosting & Random Forest classifier.
All the ensemble techniques are performed by a combination of setting weights to the classes and introducing under sampling techniques.

Random Forest classifier with Balanced Bootstrapped samples performed well on the test set.

Balanced accuracy score on Test set is: 0.7786989795918368

Recall on Minority class (risky client) is 0.64.
Out of 28 negative samples in the test, it predicted 18 of them correctly. 
Confusion matrix is provided in the notebook.

Note:
There is a scope to improve the model by doing hyperparameter tuning using bayesian search provided by hyperopt.
Beyond this we need more samples otherwise it can be prone to overfitting.

