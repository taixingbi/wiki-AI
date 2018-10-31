# topics modeling

discovering topics in a collection of documents.  


### Latent Dirichlet Allocation(LDA)     
Allows sets of observations to be explained by unobserved groups that explain why some parts of the data are similar.   
mixture of topics     

step1: tokens   
step2: create dictionary    
step3: create tf-idf    
step4: train LDA model, set number of toptics  
   
  1) Randomly choose a distribution over topics         
  2) For each word (to be created) in the document       
    a) Randomly choose a topic from the distribution over topics in step #1      
    b) Randomly choose a word from the selected topic, that is, the corresponding distribution over the vocabulary  


p(topic t’ | document d) * p(word w | topic t’)     


* application
* doc similarity 


### Graph-based ranking algorithms     
* KeyGraph         
1) Build a keywords co-occurrence graph for the given document collection      
2) Community detection and extraction of topic features      
3) Assigning topics to documents (based on the detected topic features)     
4) Merging topics with significant document overlap     

* TextRank              
voting, recommendation. based google pagerank.  
when node A links to the node B, it is basically casting a vote for B. the higher the number of votes a node receives, the higher is its importance (in the graph).   

# preference    
[1] [Text mining methods:Topic modelling & Graph-based keywords extraction](http://ai.fon.bg.ac.rs/wp-content/uploads/2017/01/Topic_modeling_and_graph-based_keywords_extraction_2017.pdf)
