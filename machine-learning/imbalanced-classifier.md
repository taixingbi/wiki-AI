# imbalanced data:
  1. get more data         

  2. random oversampling the minority with replacement    
    better than undersampling, lead overfitting     
    SMOTE     
    1. identify the feature vector and its nearest neighbour with replacement      
    2. take difference between the two, and multiply the difference with a random number between 0 and 1     
    3. identify a new point on line segment by adding the random number to feature vector     
    4. repeat the process for identified feature vectors.     
    
  3. random undersampling the majority     
    lost important samples     
    Tomek

  4. Cluster-Based Over Sampling      
    cluster for minority and majority, all cluster is the same number.      
      k-mean    
      * pros:          
      * cons: over-fitting      
          
  
# metrics     
  trade-off between recall and precision (e.g. precision is imprtant for credit card fraud detection)     
  * recall  
  * precision   
  * AUROC            

# Cost-sensitive Learning      
  penalize misclassifications of the minority class   
  
  . pro.    
  it increases the true positive rate  
    
  e.g. L2:  lamda reverse sample number.  
  

# Ensemble Techniques        
   * bagging-based    
      . pros        
      1 Improves stability & accuracy of machine learning algorithms      
      2 Reduces variance, overcomes overfitting     
      3 Improved misclassification rate of the bagged classifier      
      4 In noisy data environments, bagging outperforms boosting     
       
      . cons      
      Bagging bad classifiers can further degrade performance  

   * boosting-Based (XG-boost)     
       combine weak learners to create a strong learner     
       
      . pros      
      1 Very Simple to implement      
      2 Good generalization, Not prone to overfitting      
      
      . cons      
      Sensitive to noisy data and outliers  
      
 # biased prediction
   1. credit card fraud    
   2. rare disease dignosis     
   3. manufacturing defects     
 
 
 
 
 
 
