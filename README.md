# Amazon_Vine_Analysis

## Overview
In this challenge, we are analyzing reviews written by members of the paid Amazon Vine program. The dataset we decided to analyze was the Toys category. We imported thousands of actual reviews for products sold on Amazon, and organized into a cloud-hosted database using AWS (Amazon Web Services). Then, we connected it to our SQL databse so we could manipulate the data. The purpose of this was to avoid storing extremely large files locally, and instead store them using cloud services, available for use by members of our team who may be in another location. We wanted to analyze the percent of Vine reviews compared with non-Vine reviews to see if there is a positive bias toward certain products. 

## Results
https://github.com/rharazim/Amazon_Vine_Analysis/blob/main/Resources/vine_df.png
https://github.com/rharazim/Amazon_Vine_Analysis/blob/main/Resources/amazon_vine_analysis.png
-In total, there were 30,414 5-star reviews. Of those 30,414 reviews, 432 were part of the Vine program (paid), and the other 29,982 were not (unpaid).
-Vine reviews accounted for 1.42% of total 5-star reviews.
-Non-vine reviews accounted for 98.58% of total 5-star reviews.

## Summary
Vine reviews accounted for under 2% of total 5-star reviews, so the reviews can be seen as reliable due to the scarcity of biased, paid reviews. Over 98% of the 5-star reviews were from unpaid sources, likely from actual customers who purchased the products and were satisfied. I noticed while reviewing the data that a majority of the Vine reviews were for products of very well-known toy companies. If I were to conduct additional analysis, I would cross-reference the product descriptions of Vine reviews with a list of the top 10 toy companies to see the percentage of paid reviews they make up. 
