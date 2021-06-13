# Amazon Vine Analysis 

Syed Ahmed 
June 13, 2021 


## Overview 
 
In this project, I will be analyzing Amazon automobile reviews by using PySpark to perform an ETL process to extract the review dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into a SQL database. I will then use PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset.

## Resources 
> Link to cloud dataset: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Automotive_v1_00.tsv.gz 

## Results 

The ETL process can be found in the Amazon_Reviews_ETL.ipynb file. The following is an image of one of the tables created in this process. 

Here, I will be discussing the results of the Amazon Vine reviews analysis. 

How many Vine reviews and non-Vine reviews were there?
- As you can see from the image, the number of Vine reviews was 82 and the number of non-Vine reviews was 24,742 

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- The number of 5 star Vine reviews is 33, while the number of non-Vine 5 star reviews is 12,807

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- The percentage of Vine reviews that are 5 star is: 40.24% and the percentage of non-Vine reviews that are 5 star is 51.76%

## Summary 
