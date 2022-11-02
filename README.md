# Amazon Vine Analysis

## Overview

Using Pyspark, AWS and pgAdmin, we are going to extract raw data of product reviews, clean it for optimal use and upload it to an AWS RDS database. We are then going to analyze the results of our Vine review data.

## Results

The products we are doing these analyses are on tools.

### Total Reviews
- There are only 285 confirmed paid reviews vs. 31,545 unpaid reviews

![Vine_Reviews](https://user-images.githubusercontent.com/108296899/199545651-7dc5c22a-26d7-483e-bb6b-fc3e9d67b664.png)

![nonVine_reviews](https://user-images.githubusercontent.com/108296899/199545682-397633c3-4f7a-4d7d-bf3b-240774cbcb97.png)

### 5-Star Veviews
- There are 163 paid 5-star views vs. 14,614 unpaid 5-star reviews

![Vine_5star](https://user-images.githubusercontent.com/108296899/199546167-9710165b-5868-46d3-aa77-aeb767c4077e.png)

![nonVine_5star](https://user-images.githubusercontent.com/108296899/199546191-d0e5ee6d-a4a5-422f-bc19-4592b49382d4.png)

### Percentage of 5-star Reviews
- 57.2% of paid reviews are 5-star

![vine_percent](https://user-images.githubusercontent.com/108296899/199546449-18c6a94b-f855-4540-9033-967b25674589.png)

- 46.3% of unpaid reviews are 5-star

![nonVine_percent](https://user-images.githubusercontent.com/108296899/199546498-6651b9af-b612-4fe3-871a-ebfef9c04584.png)

## Summary

Based on this data, we can argue that customers are more likely to review a product favorably if they have confirmed a purchase of it. Another metric we can test would be the favorability of a review compared to the cost of the product. Perhaps customers would be harsher critics of a product if they spent more money on it.
