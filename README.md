# Amazon_Vine_Analysis
## Overview 
Stakeholders have asked for analysis of Amazon reviews written by members of the paid Amazon Vine program.  The dataset selected was the sports category.  It contains reviews of sprots prodcuts.  Using Pyspark to perform ETL process to extract dataset, transofrm the dta, connecto to an AWS instance and load the data into pgAdmin.  Then using Pyspark determine if any bias toward favorable reviews from Vine member.  
## Results: Using bulleted lists and images of DataFrames as support, address the following questions:
### Vine Reviews
![alt text](https://github.com/bmliddicoat/Amazon_Vine_Analysis/blob/7422575d6d79ea5a3a1b44bcbf98e848a292b2b6/images/paid_result.jpg)

* Total Paid Reviews on Sports was 334
* Total Number of Vine five star reviews was 139
* Percentage of 5 star reviews was 41.62%

### Non-Vine Reviews
![alt text](https://github.com/bmliddicoat/Amazon_Vine_Analysis/blob/7422575d6d79ea5a3a1b44bcbf98e848a292b2b6/images/no_paid_results.jpg)

* Total Non-Vine Reviews on Sports was 61,614
* Total of Five Star reviews from non-Vine was 32,665
* Percentage of five star reviews was 53.02%


## Summary
In looking at the data, there seems to be no bias.  Actually, Vine program memembers found items less favorable (41.62%) than non-Vine(53.02%).  This lower percentage for favorable amongst Vine users indicates a lack of potential bias.  To further expose non-bias or bias behaviors by users, a random number of products would need to be generated.  An analaysis of these random products could be used to compare by reviews results.  You could instead look at number of negative reviews (1 star or whatever metric shows negative feel on a product).  This could determine if Vine users are less likely to give negative review than non-Vine users.  Less negative cores could increase the mean rating of  a product. 
