# classification:   

* ![alt text](https://i.stack.imgur.com/OW5Lt.jpg)

 * precision (true positive rate)     
 * recall(sensitive)     



* Receiver operating characteristic(ROC) curve    
For binary classifier, graphical plot shows its discrimination threshold is varied.   
it plots the true positive rate (TPR) against the false positive rate (FPR)   

 
 ![alt text](https://wikimedia.org/api/rest_v1/media/math/render/svg/26106935459abe7c266f7b1ebfa2a824b334c807  
)(true postive rate)          
 ![alt text](https://wikimedia.org/api/rest_v1/media/math/render/svg/af37c5d528612c6dce5987718585ae5313abf79a)     

 ![alt text](http://scikit-learn.org/stable/_images/sphx_glr_plot_roc_001.png)

* discrimination threshold 
 threshold is balanced between cases and set to 50% probability.

 ![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4f/ROC_curves.svg/709px-ROC_curves.svg.png)

  


# regression:
* root mean sqaure error(RMSE)     

 ![Screenshot](https://cdn-images-1.medium.com/max/1600/1*OVlFLnMwHDx08PHzqlBDag.gif)




* mean abslute error(MAE)

 ![Screenshot](https://cdn-images-1.medium.com/max/1600/1*9hQVcasuwx5ddq_s3MFCyw.gif)

* coefficient of determination(R squared)         
percentage of total variation in the response variable by the least sqaure regression.      


 ![Screenshot](http://social.technet.microsoft.com/wiki/resized-image.ashx/__size/550x0/__key/communityserver-wikis-components-files/00-00-00-00-05/6787.6.jpg)         

Tips: Best score is 1.0, about 0.07 is good.  it is 0 disregarding the input feature. it could be negative. 
