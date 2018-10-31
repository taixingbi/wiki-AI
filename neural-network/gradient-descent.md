# gradient descent   
first-order iterative optimization algorithm to find the minimum of a function   

#### stochastic gradient descent(SGD)
computes the parameters gradient using only one sample or a few samples(mini-batch) examples.

#### adaptive moment estimation(Adam)
computes adaptive learning rates for each parameter--exponentially decaying average of past squared gradients

* process   
step 1 Initialize the weights W randomly.  
step 2 Calculate the gradients    
step 3 Update the weights   
setp 4 Repeat until the loss stops reducing    


#### tips 
* randomly shuffle samples   
not shuffle cause local minima or slower convergence  
option 1: randomly once with no replacement  
option 2: randomly for each batch with replacement   
sampling without replacement(option1), leads to faster convergence than sampling with replacement(option2).   
