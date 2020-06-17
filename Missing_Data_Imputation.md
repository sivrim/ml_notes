### Excerpts from http://www.stat.columbia.edu/~gelman/arm/missing.pdf


Impact of missing or incorrect data  
Impact of removing data  
Impact of imputing data  
Effort and impact of different cleaning methods.   

Complete case analysis  
Modelling missing data process.  

### Missingness mechanisms
##### Why the data is missing  
1. Completely at random --> Throwing data doesn't bias the inferences.
2. At Random -->   
       Ignorability assumption --> Assumption that the probaiblity of data missing is depedent only on available information.   
       Include predictors for variables that affect the proability of missingness.
2. Missingness that depends on unobserved predictors
      Explicitly model or else accept some bias in inferences.
4. Missingness that depends on the missing value itself
      E.g., suppose that people with higher earnings are less likely to reveal their earnings. Exterme cases would become censoring.
      Model or mitigate by including more relevant predictors in the missing-data model and thus bringing it closer to missing-at-random scenario.
      

      
      
      
      
