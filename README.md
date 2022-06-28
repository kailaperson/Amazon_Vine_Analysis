# Amazon_Vine_Analysis

## Overview of the analysis
- The purpose of this analysis is to review a specific dataset and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. After this is done, PySpark will be used to determine if there is any bias toward favorable reviews from Vine members in the dataset. This information will be used to submit to SellBy stakeholders.

## Results
- The data showed that were 1080 Vine reviews.
![Screen Shot 2022-06-28 at 11 44 32 AM](https://user-images.githubusercontent.com/97639454/176258667-f46af78f-3e82-433c-9883-3996ea0b9e36.png)

![Screen Shot 2022-06-28 at 11 41 40 AM](https://user-images.githubusercontent.com/97639454/176258247-9b8bedd3-c1e2-4338-aa8f-2791a6a33a4b.png)

- The data also showed that there were 49673 non-Vine reviews.
![Screen Shot 2022-06-28 at 11 42 44 AM](https://user-images.githubusercontent.com/97639454/176258387-15259ef0-36d3-4538-aa55-60dfb3949e0b.png)

![Screen Shot 2022-06-28 at 11 45 25 AM](https://user-images.githubusercontent.com/97639454/176258842-d7d0e8ad-81d7-405f-affe-a373f9f77852.png)

- The date yieled that 454/1080 of Vine reviews  were 5 stars, and 23043/49673 of non-Vine reviews were 5 stars.

- This means about 42% of Vine reviews were 5 stars, and about 46% of non-Vine reviews were 5 stars.

## Summary
- Determing the data based on 5 star results does not seem to show bias for Vine reviews being that the number of 5 star reviews are close in range for non-Vine reviews.

- One additional analysis that could help would be to filter verified purchases. In the image of the Vine reviews in the results section we can see how the  first 20 rows show that that those purchases were unverified. This could mean the reviews may infact be biased. 
