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

Due to the minimal number of reviews from people in the Vine program (170), it is recommended that a similar analysis be done on several different product review sets to determine if, with a larger data set, people in the Vine program tend to score products higher than those not in the program. Deeper analysis could be done using an ANOVA or Chi squared test which might better normalize the difference in the population numbers and give more accurate results. 

It is also recommended to look at other numbers on the rating scale. Do Vine reviewers lean toward positivity within 3 to 5 stars rather than just 5 stars. Do Vine reviewers lean toward negativity by giving more 1 and 2 star ratings?

It is also recommended to consider the consistency in which people who are not participating in the Vine program actually give reviews. Do some people give more positive ratings while others give more negative ratings? Can these people be identified and removed from the analysis to compare Vine reviewers to those not participating in the Vine program who consistently review and offer a variety of reviews. Are there similar types of people in the Vine program? Would we want to consider removing them from the analysis?
