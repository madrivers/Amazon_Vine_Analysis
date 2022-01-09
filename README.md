# Amazon_Vine_Analysis

## Analysis Overview

The projects reviews data from customer reviews regarding a variety of Video Games.  The purose of the data review is to determine if there is bias for favorable reviews from customers whom are paid for feedback versus those whom are not.

This analysis leverages PySpark to perform the work.  The work comprises Extracting data from a base source, Transforming that data to meet a pre-determined format and Loading that data into a database (pgAdmin in this case).

## Results

Total Number of Reviews:

![Total Reviews](https://github.com/madrivers/Amazon_Vine_Analysis/blob/main/Resources/Total%20Reviews.png)

Paid Reviews totaled 94 while unpaid totaled 40,471

Total Number of 5-Star Reviews:

![5 Star Reviews](https://github.com/madrivers/Amazon_Vine_Analysis/blob/main/Resources/5_Star_Reviews.png)

5 Star Paid Reviews totaled 48 while UnPaid 5 Star Reviews totaled 15,663

Percentages of Paid and Unpaid 5 Star Reviews of Total Paid Reviews:

![Percentages](https://github.com/madrivers/Amazon_Vine_Analysis/blob/main/Resources/Percentages.png)

Paid 5 Star reviews comprised approximatly half or 51% of total paid reviews while Unpaid 5 Star Reviews comprised nearly 39% of non paid reviews.

# Summary

This data concludes that paid reviews are more likely to rate at a 5 star level than unpaid.  A regression analysis could be leveraged to gain further insight into the correlation of paying for a review and its rating.
