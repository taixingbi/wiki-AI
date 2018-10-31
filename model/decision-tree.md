A decision tree uses a tree-like graph and their possible consequences, 
including chance event outcomes, resource costs, and utility for classification and reression

* Gini impurity
how often a randomly chosen element would be incorrectly labeled.    
Gini = 1 − ∑ P(x)**2   

* Information gain    
decide which feature to split on at each step in building the tree.     
Information gain= parent entropy - weighted sum of children entropy      
IG(T,a)= H(T) - H(T/a)    

  Entropy    
  H(x)= −∑ P(x)log P(x)  p is probability for a random variable
  
  
* pros  
  1. Simple to understand and interpret.    
  2. Able to handle both numerical and categorical data.   
  3. Uses a white box model.    
  4. Performs well with large datasets.    

* cons     
  1. Trees can be very non-robust. A small change in the training data can result in a large change.    
  2. low bias, but very high variance, overfitting.    
  3. Decision-tree learners can create over-complex trees that do not generalize well from the training data
  
