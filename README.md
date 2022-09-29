# Amazon_Vine_Analysis

### Overview of the analysis: 

The purpose of this analysis was to determine if there is any bias towards favorable reviews from Vine members within this dataset. This was done by extracting the data sets, and using PySpark to perform the ETL process by connecting to a AWS RDS instance, and loading the data sets into pgAdmin. Later the vine data was loaded into Pandas where the data was analyzed further. 
### Results: 
![Results](https://raw.githubusercontent.com/SavannahPosner/Amazon_Vine_Analysis/main/Screen%20Shot%202022-09-29%20at%2010.46.11%20AM.png)





### Summary: 
There is no evidence of a positive bias towards reviews in the Vine Program. Based on this analysis, the post less, and they have a lower percentage of five star reviews than Non-Vine users.

In terms of further analysis, another way to view the feedback of the Vine reviews relative to the total reviews, would be to calculate the mean of the Vine reviews and compare it to the mean of the total reviews. Just because they don’t have a higher proportion of five start reviews, doesn’t mean their overall review status isn’t higher than that of the total reviews. 
