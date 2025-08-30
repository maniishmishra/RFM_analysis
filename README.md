RFM Analysis using Python

Analyzing Customer Segmentation in Online Retail Datasets with Python, including cohort analysis, understanding purchase patterns, and cluster analysis with RFM.



Getting started In the following analysis, I am going to use the Online Retail Data Set, which was obtained from the UCI Machine Learning repository. The link to the data can be found here. In this article, I am going to write about how to carry out customer segmentation and RFM analysis on online retail data using python. Data This data set contains all of the transactions recorded for an online retailer based and registered in the UK. The retailer specializes in all-occasion gift items. Most of the retailer’s customers are wholesalers. Column Descriptions


Column Name	Description	Data Type
InvoiceNo	Invoice number.If this code starts with letter 'c', it indicates a cancellation.	Nominal, a 6-digit integral number uniquely assigned to each transaction
StockCode	Product (item) code	Nominal, a 5-digit integral number uniquely assigned to each distinct product
Description	Product (item) name.	Nominal
Quantity	The quantities of each product (item) per transaction.	Numeric
InvoiceDate	Invice Date and time	Numeric, the day and time when each transaction was generated
UnitPrice	Unit price	Numeric, Product price per unit in sterling
CustomerID	Customer number	Nominal, a 5-digit integral number uniquely assigned to each customer
Country	Country name	Nominal, the name of the country where each customer reside

Plan

Reading data and preprocessing
Create Recency Frequency Monetary (RFM) table
Model — Clustering with K-means algorithm
Interpret the result
