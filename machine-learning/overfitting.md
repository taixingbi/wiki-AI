# overfitting
a model learns the detail and noise in the training data. high variance and low bias.

# solution:
#### 1. collect more data

#### 2. feature selection
more features means more variance.

#### 3. penalize regularization
increase regularization coefficient λ

L1: λ ∑|w|  sum of the abslute weights   
L2: λ ∑|w|**2  sum of the square weights    

L2 is better.    
. computational effient     
. non-sparse outputs       
. no feature selection     

#### 4. increase dropout    

#### 5. simpler model: always modeling from baseline

#### 6. stop tarning before overfitting happen

overfitting: loss for validation data increase while training data is still decrease

# metrics
#### cross validation  
