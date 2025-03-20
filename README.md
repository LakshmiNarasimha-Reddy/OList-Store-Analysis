# OList-Store-Analysis

## Introduction
Olist is a Brazilian e-commerce platform that connects small and medium-sized businesses to customers across Brazil. The platform operates as a marketplace, where merchants can list their products and services and customers can browse and purchase them online.The dataset is designed to help analysts and researchers better understand the e-commerce landscape in Brazil and identify opportunities for growth and optimization. To help Olist gain better insights into its e-commerce platform and optimize available opportunities for growth,we will perfom some KPI's and answer some business questions,thereby providing Insights and recommendations.

## Data Description
The features allow viewing orders from multiple dimensions: from order status, price, payment, and freight performance to customer location, product attributes, and finally reviews written by customers.
For this challenge, I used Power Query to access the dataset, clean and perform Data Analysis using BI tool Tableau , Power BI and Excel.

Below is the outline of the challenge

* Explore Dataset and perform Data Validation
* Data Cleaning
* Perform KPI's Data Analysis
* Share Insights and Make recommendations

## Dataset and Dictionary 
The Olist dataset comprises nine separate datasets, all of which are stored in CSV format:

1. olist_order_items_dataset
2. olist_orders_dataset
3. olist_order_payments_dataset
4. olist_order_reviews_dataset
5. olist_products_dataset
6. olist_customers_dataset
7. olist_sellers_dataset
8. olist_geolocation_dataset
9. olist_category_dataset

The olist data dictionary that offers a complete overview of the dataset. This data dictionary is a valuable reference as it provides in-depth explanations of each variable and its significance within the dataset. It serves as a useful tool for understanding and interpreting the data effectively.

## Data Schema
![image](https://github.com/LakshmiNarasimha-Reddy/OList-Store-Analysis/blob/d7ef2bc59722bc28e217cd1ad32998980f5bbe3f/Joins.png)

## Data Exploration & Validation
I explored the 9 different tables with Excel and from this process, I discovered the dataset had the following quality issues:

* Null & Empty values
* Unwanted special characters
* Irrelevant columns
* Errors in spelling.



