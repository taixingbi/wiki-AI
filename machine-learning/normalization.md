# normalization

#### 1. Min-max normalization 
  z= (x-min)/(max-min)

  * pro:   
  preserve range (maximum and minimum)   
  linearly transformed (0, 1)   

####  2. Z-score normalization
  z= (x-mean)/standard deviation    
  standard deviation: root mean square deviation    
  data based on gaussian distribution    

####  3. sigmoid normalization (-1, 1)
  z= 1/(1+e**-x)    
  sigmoid curve     

####  3. Constant Normalization
  divide by a constant     

####  4. Binary Encoding

####  5. Manhattan Encoding(one hot)    

  pros     
  1. it removes any bias in model   
  2. it converges faster    
  cons    
