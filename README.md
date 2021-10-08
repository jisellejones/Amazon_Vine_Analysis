# Amazon_Vine_Analysis

## Overview
The purpose of this analysis was to determine if there is any positivity bias in the reviews of Pet products by people who are part of Amazon's Vine program.

## Data Source
- [Amazon Pet Product Reviews](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Pet_Products_v1_00.tsv.gz)

## Software
- Google CoLab
- Spark version 3.0.3

## Results

#### Vine Reviews
- The total number of reviews was minimal at 170.
- The total number of 5-star reviews was 65.
- The percentage of reviews that were given 5-stars was 38%

*Table Showing Vine Reviews*
| Total Review Count | 5-Star Review Count | % of 5-Star Reviews | 
|--------------------| ------------------- | ------------------- |
| 170 | 65| 38 |


#### Non- Vine Reviews
- The total number of reviews was much larger than the number of Vine reviews at 37,840.
- The total number of 5-star reviews was 20,612.
- The percentage of reviews that were given 5-stars was 54%.

*Table Showing Non-Vine Reviews*
| Total Review Count | 5-Star Review Count | % of 5-Star Reviews | 
|--------------------| ------------------- | ------------------- |
| 37,840 | 20,612 | 54 |

## Summary

The analysis did not show positivity bias in the reviews of people in the Vine program. In fact, only 38% of people in the Vine program gave 5-star reviews, while 54% of people not participating in the vine program gave 5-star reviews. 

Due to the minimal number of reviews from people in the Vine program (170), it is recommended that a similar analysis be done on several different product review sets. 
