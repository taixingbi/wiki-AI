# Random forests 
Random forests(random decision forests) are an ensemble learning method for classification, regression and 
other tasks(feature selection), constructing a multitude of decision trees at training time and outputting the class (classification) or mean prediction (regression) of the individual trees.   
    
##### step 1: bootstrap（bagging)     
random sample with replacement      
it decreases the variance of the model, without increasing the bias     

##### step 2: Random subset of the features(feature bagging)    
at each candidate split, random samples of features instead of the entire feature set    
correlation of the trees in an ordinary bootstrap sample     

* pros:    
1. make model simple to interpret.      
2. reduce the variance of the model, and therefore avoid overfitting     
3. handle missing data       
4. handle large data with high dimentionality   
5. reduce the computational cost (and time) of training a model.   

* cons:    
1. good job at classification not as good as regression    
2. very little control on what model does     

