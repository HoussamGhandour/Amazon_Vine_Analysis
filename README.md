# Amazon_Vine_Analysis

## Overview of Analysis

The purpose of this analysis is to Extract, Transform, and Load Pet Products reviews from Amazon S3 data storage. Our team further examined the review data to determine whether reviews through vine paid programs had an impact on the review rating of the product.

## Results

In order to focus on helpful reviews, our team filtered on rows that have at least 20 total votes on the review. In addition, the data was further filtered to only include the rows which have at least 50% helpful votes out of the total. The results for paid and unpaid program reviews are listed below:

- The total number of unpaid reviews was: 37840
- The total number of unpaid reviews with 5 stars was: 20612
- The total percentage of unpaid reviews with 5 stars was: 54.47%
- The total number of paid vine reviews was: 170
- The total number of paid vine reviews with 5 stars was: 65
- The total percentage of paid vine reviews with 5 stars was: 38.24%

The image below shows the output results detailed above: 

<p align="left"> <img src="/Resources/Results.PNG" width="500"> </p>

## Summary

Our team concluded that there is not a positivity bias for paid vine program reviews as it seems that the percentage of 5 stars review was lower than the unpaid review. However, our team cannot conclude a negativity bias either. Further analysis should be done as the results were not expected. Our team recommends analyzing an average rating instead of only focusing on 5 stars review. It would be interesting to look at how many 1 through 4 stars ratings each dataset has and compare averages for more detailed analysis.
