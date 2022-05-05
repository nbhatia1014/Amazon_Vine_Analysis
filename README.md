# Amazon_Vine_Analysis
data set: https://s3.amazonaws.com/amazon-reviews-pds/tsv amazon_reviews_us_Video_Games_v1_00.tsv.gz

## Overview:

### Purpose:
The purpose of this project is to assist Jennefir by analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. We will use PySpark to determine if there is any bias toward favorable reviews from Vine Members.

## Results:

### Vine Review Overview:
Shown below are the results of the data when filtered by the Amazon Vine program.

- Total Reviews:

![This is an image](https://github.com/nbhatia1014/Amazon_Vine_Analysis/blob/main/Images/Total_Paid_Reviews.PNG)

- Total 5-Stars

![This is an image](https://github.com/nbhatia1014/Amazon_Vine_Analysis/blob/main/Images/Total_Paid_5Star_Reviews.PNG)

- Percentage of 5-Stars

![This is an image](https://github.com/nbhatia1014/Amazon_Vine_Analysis/blob/main/Images/Paid_Percentage.PNG)

### Non-Vine Overview:

- Total Reviews:

![This is an image](https://github.com/nbhatia1014/Amazon_Vine_Analysis/blob/main/Images/Total_Unpaid_Reviews.PNG)

- Total 5-Stars

![This is an image](https://github.com/nbhatia1014/Amazon_Vine_Analysis/blob/main/Images/Total_Unpaid_5Star_Reviews.PNG)

- Percentage of 5-Stars

![This is an image](https://github.com/nbhatia1014/Amazon_Vine_Analysis/blob/main/Images/Unpaid_Percentage.PNG)

## Summary:

### Comparison / Bias
Overall, the non-paid reviews had a larger sample when compared to the paid reviews. That being said, the paid reviews overall were likely to be 5-stars. This could present a positivity bias towards the reviews coming from teh vine program. However, with the lack of sample it could also be a selection bias. Additionally, we could do the df.stats function to show the statistical distribution and determine if there is any data that needs to be removed.












