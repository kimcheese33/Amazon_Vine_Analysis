# Amazon Vine Analysis

## Overview

The purpose of this analysis was to analyze Amazon reviews written by reviewers paid by the Amazon Vine program. This program allows companies to receive reviews for their products written by Vine members who are receive the products and are required to publish a review. For the project I used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. I then used Pyspark to analyze the data to determine if any bias existed from Vine member reviews.

## Results

-- There were 616 Vine (paid) reviews and 69,432 non-Vine (unpaid) reviews.

-- There were 12,429 5-star Vine reviews and 3,242,324 5-star non-Vine reviews.

-- 0.38% of Vine reviews were 5 stars and 99.62% of non-Vine reviews were 5 stars.


## Summary

Based on the analysis, only 0.38% of 5 star reviews came from the Vine program. Therefore, there is no evidence to suggest there is positivity bias coming from the Vine program. An additional anaylsis I could do to support this would be to check the percentage of Vine reviews for the other star rating categories. For example, we could see what percentage of Vine reviews gave 4 star reviews. A high percentages of 4 star reviews from Vine reviewers could indicate some positivity bias.
