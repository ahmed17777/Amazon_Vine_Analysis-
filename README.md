# Amazon Vine Analysis 

Syed Ahmed 
June 13, 2021 


## Overview 
 
In this project, I will be analyzing Amazon automobile reviews by using PySpark to perform an ETL process to extract the review dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into a SQL database. I will then use PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset.

## Resources 
> Link to cloud dataset: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Automotive_v1_00.tsv.gz 

## Results 

The ETL process can be found in the Amazon_Reviews_ETL.ipynb file. The following is an image of one of the tables created in this process. 

![1](https://user-images.githubusercontent.com/45697471/121825265-60178880-cc7f-11eb-9a19-813201ee95ff.png)


Here, I will be discussing the results of the Amazon Vine reviews analysis. 

![paid](https://user-images.githubusercontent.com/45697471/121825267-6443a600-cc7f-11eb-879e-b6a2015e3859.png)

![unpaid](https://user-images.githubusercontent.com/45697471/121825271-67d72d00-cc7f-11eb-8855-8fc22884bc52.png)


#### How many Vine reviews and non-Vine reviews were there?
- As you can see from the image, the number of Vine reviews was 82 and the number of non-Vine reviews was 24,742 

#### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- The number of 5 star Vine reviews is 33, while the number of non-Vine 5 star reviews is 12,807

#### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- The percentage of Vine reviews that are 5 star is: 40.24% and the percentage of non-Vine reviews that are 5 star is 51.76%

## Summary 

40% of the reviews in the paid Vine program were 5 stars, whereas the unpaid non-Vine reviews had 52% five star reviews. This means there is a negativity bias for reviews in the Vine program for automobiles. Additional analysis that could be done includes: 
- Looking at measures of central tendency (mean, median, mode) of the ratings (Vine vs non-Vine) 
- Normalizing the datasets to create a more statistically meaningful analysis 


### Contact 
Email: mishaal22s@gmail.com
