# Amazon_Vine_Analysis
## Resources Used
- Google Colab, PostgreSQL, Amazon Web Services, PySpark

## Project Overview

In this project, we analyzed Amazon reviews from the Amazon Vine Program. Using a dataset based on reviews on beauty products, we used PySpark to perfrom an ETL and connected the data to an Amazon Web Service RDS instance. Ultimately, we turned this into 4 tables in pgAdmin (customers_table, products_table, review_id_table, vine_table). Using Google Colab, we performed an analysis to determine if there was any bias in the dataset using PySpark again.

## Results

## Total Vine Reviews vs. Non-Vine Reviews
![total_paid](https://github.com/rhiandoy/Amazon_Vine_Analysis/blob/3577babc7998513b844ad339315001ba484c38eb/images/total_paid.png)
![total_unpaid](https://github.com/rhiandoy/Amazon_Vine_Analysis/blob/3577babc7998513b844ad339315001ba484c38eb/images/total_unpaid.png)

- The amount of total Non-vine (non-paid) reviews for Amazon Beauty Products was 74,113 while the paid reviews were a lot lower at 647

## Five Star Vine Reviews vs. Five Star Non-Vine Reviews
![five_paid](https://github.com/rhiandoy/Amazon_Vine_Analysis/blob/3577babc7998513b844ad339315001ba484c38eb/images/five_star_paid.png)
![five_unpaid](https://github.com/rhiandoy/Amazon_Vine_Analysis/blob/3577babc7998513b844ad339315001ba484c38eb/images/five_star_unpaid.png)

- The 5-star vine reviews were at 229 while the non-vine were at 43,217

## Percentage of Five Star Vine vs. Percentage of Five Star Non-Vine
![paid_percent](https://github.com/rhiandoy/Amazon_Vine_Analysis/blob/3577babc7998513b844ad339315001ba484c38eb/images/paid_percent.png)
![unpaid_percent](https://github.com/rhiandoy/Amazon_Vine_Analysis/blob/3577babc7998513b844ad339315001ba484c38eb/images/unpaid_percent.png)

- The 5-star vine percentage was around 35.4% 
- The 5-star non-vine percentage was around 58.3%

## Summary

According to my analysis of the Amazon Vine Program, the beauty product reviews in the program did not show positive bias. For each analysis of the data the unpaid reviews were much higher than the paid reviews. While this analysis showed a non positive bias toward the vine program, we could dive further into this by analyzing multiple different datasets such as eletronics, home goods, etc. 
