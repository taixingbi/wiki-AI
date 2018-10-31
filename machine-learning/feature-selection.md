# feature selection

#### benifit
  * Reduces Overfitting: less opportunity to make decisions based on noise.
  * Improves Accuracy: Less misleading data 
  * Reduces Training Time

#### solution 
* 1. feature importance(tree based)
extra tree vs random forest.    
acieve the performace, extra tree is three times faster in Sciklearn.    

* 2. principle component analysis(unspuervised)  
uses linear algebra to transform the dataset into a compressed form.

* 3. Univariate Selection  
each feature individually to determine the strength of the relationship of the feature with the response variable  
  Pearson's Chi squared test   

* 4. Recursive Feature Elimination.
recursively considering smaller and smaller sets of features
. logistic regression

* 5. L1 norm (select from model)
select the non-zero coefficients
svm + L1
