# Cross validation
Cross validation(or rotation estimation, out-of-sample testing) is any of various similar model validation techniques for assessing how the results of a statistical analysis will generalize to an independent data set.

#### k-fold cross-validation
dataset is randomly partitioned into k equal sized folds. one fold is the validation data, and k−1  folds ares training data  

* typically  K = 5 or 10    

![Sreenshot](https://qph.fs.quoracdn.net/main-qimg-3a101fe2f7db6ceb145c13e9c16defea.webp)



* pros    
all folds are used for both training and validation to maximize the use of the available datasets. helpful when number of samples is very small.

#####  Time Series Split
variation of k-fold returns first k folds as train set and the (k+1)th fold as test set       
![Sreenshot](http://scikit-learn.org/stable/_images/sphx_glr_plot_cv_indices_0101.png)   

#### types
* Exhaustive cross-validation
learn and test on all possible ways to divide the original sample into a training and a validation set   

* Non-exhaustive cross-validation(k-fold)
not compute all ways of splitting the original sample, approximations of leave-p-out cross-validation

*  stratified k-fold cross-validation       
folds preserve roguhly same percentage of samples for each class.



