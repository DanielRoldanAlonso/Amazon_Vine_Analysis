# Amazon_Vine_Analysis

## Overview of the Analysis

The purpose of this analysis was to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. We selected video games as ou dataset and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. After we used PySpark to determine if there is any bias toward favorable reviews from Vine members in our dataset.

## Results
![reviews](Images/reviews.PNG) 
- From our analysis, there was 94 paid reviews and 40,471 unpaid reviews.

![five_star_reviews](Images/five_star_reviews.PNG) 


![five_star_percentage](Images/five_star_percentage.PNG)

## Summary
