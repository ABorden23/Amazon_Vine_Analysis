# Amazon Vine Analysis

## Overview of the analysis: 

In this project we have been given access to 50 Datasets to choose from to analyze. I decided to choose sports...

The purpose of this is determine if there is any bias towards favorable reviews from Vine members in the dataset.

Software/Languages Used: 

* PySpark 
* AWS 
* ETL 
* SQL
* Pandas

## How many Vine reviews and non-Vine reviews were there?

### Paid Reviews

![paid_reviews.png](https://github.com/ABorden23/Amazon_Vine_Analysis/blob/main/resources/paid_reviews.png)

### Unpaid Reviews

![unpaid_reviews.png](https://github.com/ABorden23/Amazon_Vine_Analysis/blob/main/resources/unpaid_reviews.png)

## How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

### Paid 5 Star Reviews

![paid_5star_reviews.png](https://github.com/ABorden23/Amazon_Vine_Analysis/blob/main/resources/paid_5star_reviews.png)

### Unpaid 5 Star Reviews

![unpaid_5star_reviews.png](https://github.com/ABorden23/Amazon_Vine_Analysis/blob/main/resources/unpaid_5star_reviews.png)

## What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

### Percentage of Paid 5 Star Reviews

![percentage_paid_5star_reviews.png](https://github.com/ABorden23/Amazon_Vine_Analysis/blob/main/resources/percentage_paid_5star_reviews.png)

### Percentage of UnPaid 5 Star Reviews

![percentage_unpaid_5star_reviews.png](https://github.com/ABorden23/Amazon_Vine_Analysis/blob/main/resources/percentage_unpaid_5star_reviews.png)

Results: Using bulleted lists and images of DataFrames as support, address the following questions:

Customers Table Data Frame

![customers_table DataFrame.png](https://github.com/ABorden23/Amazon_Vine_Analysis/blob/main/resources/customers_table%20DataFrame.png)

Products Table DataFrame

![products_table DataFrame.png](https://github.com/ABorden23/Amazon_Vine_Analysis/blob/main/resources/products_table%20DataFrame.png)

Review ID Table DataFrame
![products_table DataFrame.png](https://github.com/ABorden23/Amazon_Vine_Analysis/blob/main/resources/review_id_table%20DataFrame.png)

Vine Table DataFrame

![vine_table DataFrame.png](https://github.com/ABorden23/Amazon_Vine_Analysis/blob/main/resources/%20vine_table%20DataFrame.png)

Vine Review Analysis with Pandas

![vine_review_analysis pandas.png](https://github.com/ABorden23/Amazon_Vine_Analysis/blob/main/resources/vine_review_analysis%20pandas.png)

Vine Review Analysis with SQL

![vine_review_analysis sql.png](https://github.com/ABorden23/Amazon_Vine_Analysis/blob/main/resources/vine_review_analysis%20sql.png)

## Summary: 

39.82 % of paid 5 star reviews matched the percentages of 51.62% of UNpaid 5 star reviews. 

We could always test the standard deviation, mean, median, and mode of the star ratings for the vine and now vine reviews.

In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
