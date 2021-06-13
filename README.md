# Amazon Vine Analysis 

Syed Ahmed 
June 13, 2021 


## Overview 
 
In this project, I will be analyzing Amazon automobile reviews by using PySpark to perform an ETL process to extract the review dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into a SQL database. I will then use PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset.

## Resources 
Link to cloud dataset: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Automotive_v1_00.tsv.gz 

## Results 

The ETL process can be found in the Amazon_Reviews_ETL.ipynb file. The following is an image of one of the tables created in this process. 

Here, I will be discussing the results of the Amazon Vine reviews analysis. 

How many Vine reviews and non-Vine reviews were there?
- As you can see from the image
