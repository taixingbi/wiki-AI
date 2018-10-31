
# solution  
step1 token   
step2 load pretained word2vec model, like "google news" or "glove"     
step3 bag of words with TF-IDF as weight          
       Latent semantic analysis(LSA)               
step4 compute simialrity      




# metrics 
* jaccard similarity 
[code](https://github.com/taixingbi/NLP/blob/master/text-similarity/metrics.ipynb)      
size of intersection divide size of union of two sets(unique words).  
takes only unique set of words    
duplication does not matter

   ![Screenshot](https://upload.wikimedia.org/math/1/8/6/186c7f4e83da32e889d606140fae25a0.png)    


* consine similarty
convert sentences into vectors, bag of words with TF-IDF     
takes total length of the vectors   
duplication does matter

   ![alt tag](https://camo.githubusercontent.com/53b91d3e027d443511db160792e5c30a0a3591d2/68747470733a2f2f63646e2e7261776769742e636f6d2f636f6d707574652d696f2f636f73696e652d73696d696c61726974792f626465663934306266346536643332306432363532623532663534663538636632656135643739342f646f63732f696d672f65716e5f73696d696c61726974792e737667)

