# category

* Missing at Random (MAR)
missing is not related to the missing data, but it is related to some of the observed data.

* Missing Completely at Random (MCAR)
missing has nothing to do with its hypothetical value and with the values of other variables.

* Missing not at Random (MNAR)
. depends on the hypothetical value. 
(e.g. People with high salaries generally do not want to reveal their incomes in surveys) 
. dependent on some other variable’s value 
(e.g. Let’s assume that females generally don’t want to reveal their ages)

# solution:

* listwise  
for 1,2, it is safe, for 3, produce a bias.      
. drop colmons        
drop colmons variables if the data is missing for more than 60% observations, but only if that variable is insignificant.    
. drop all values    
removes all data for an observation that has one or more missing values.       
assumptions of MCAR are typically rare to support and produce biased parameters and estimates.        

* Pairwise       
deletes cases when one of the variables in the particular model you are evaluating is missing.   
measures the strength correlation relationship between two variables.    
increases power in your analyses    
