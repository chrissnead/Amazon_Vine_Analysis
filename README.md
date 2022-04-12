# Amazon_Vine_Analysis

## Overview
The purpose of this analysis is to look at Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. This analysis focuses on a dataset of software reviews that we pull from an AWS S3 bucket, perform the ETL process through PySpark, connect to an AWS RDS instance, and load data into pgAdmin.

## Results
Vine Reviews
- Total Reviews: 248
- Total 5-Star Reviews: 102
- Percentage 5-Star Reviews: 41%

Non-Vine Reviews
- Total Reviews: 17,514
- Total 5-Star Vine Reviews: 5,154
- Percentage 5-Star Reviews: 29%

## Summary
By the data given, the Amazon Vine program could have a slight bias for positive reviews, but for the most part they seem to be honest and comparable to non-Vine reviews. With 41% of Vine reviews holding a 5-star rating compared to non-Vine 5-star reviews consisting of 29% of the total, it can be concluded the Vine program is a great program for companies to get their products reviewed.

With the data given, we could go even further in analyzing different datasets to see if there are any similarities or differences in the Vine program data based on product category. If all datasets are comparable in their conclusion, it can be concluded even more that the program is trustworthy and beneficial to businesses looking to get their products recognized more on Amazon.
