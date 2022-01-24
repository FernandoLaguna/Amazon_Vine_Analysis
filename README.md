# Amazon Vine Analysis

## Overview

The objective of this project is analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, we will analyze the watch dataset and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I’ll use PySpark to determine if there is any bias toward favorable reviews from Vine members in your dataset. 

## Results

- How many Vine reviews and non-Vine reviews were there?
8409

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
 4332 paid and 15 non paid
 
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
 31% paid vs 52% non paid

## Summary

It is not a good idea to pay for this service, the percentage of 5 stars obtained in the free service is higher than the one that we obtained paying. Besides, the number of reviews obtained in the paid service is very low

![Dataframe](results.png)
