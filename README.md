# Sales-Data-Analysis
Exploration and Visual Analysis


# Introduction
Sales data shows the recordings of transactions between a seller and their customers. It is one of the most important documentations which every seller is required to keep. Analysing sales data can help you make informed decisions such as demand forecasting, how, where and when to run sales promotions, obsolete products and fast selling products etc.. It gives you an insight on the performance of sales. 

In this project, I am looking at analysing a dataset that was sourced from Kaggle (https://www.kaggle.com/code/knightbearr/analysis-sales-data-knightbearr/input).
The aim is to know,
1. Sales revenue based on City.
2. Revenue generation based on Month, Quarter, and Year.
3. Peak sales hours
4. Highest selling product by Revenue and Quantity

# Content

# Data Dictionary

1. Order ID - An Order ID is the number system that Amazon uses exclusively to keep track of orders. Each order receives its own Order ID that will not be duplicated.This number can be useful to the seller when attempting to find out certain details about an order such as shipment date or status.
2. Product - The product that have been sold.
3. Quantity Ordered - Ordered Quantity is the total item quantity ordered in the initial order (without any changes).
4.  Price Each - The price of each products.
5.  Price Each - The price of each products.
6.  Order Date - This is the date the customer is requesting the order be shipped.
7.   Purchase Address - The purchase order is prepared by the buyer, often through a purchasing department. The purchase order, or PO, usually includes a PO number, which is useful in matching shipments with purchases; a shipping date; billing address; shipping address; and the request items, quantities and price.
    
 # Data Preparation (Data Cleaning)
 One of the important steps in preparing data for analysis is makinng sure that the dataset is well cleaned and fit for the purpose of the analysis. As much as data  cleaning is time consuming, it is prudent that careful attention is given to it or else the final result of the ananlysis will be misleading (GABBAGE IN GABBAGE OUT).
 
 In this project, the dataset was not that messy. To get this dataset into the best shape, these activities were carried out.
 1. Removing of NA and Null Values. Since this was a sales data, I decided not to fill Na or Null values since this might give a misleading analysis result especially for these columns (Quantity Ordered and Price Each).
 2. Checking and removing Duplicated data.
 3. Setting the correct data types for each column.

# Variable Manipulation 
This process simply meaning creating of new data columns with the help of functions. This was with sole purpose of aiding in the analysis phase. The following new data columns were created 
1. Revenue (product of Quantity Ordered and Price Each)
2. Hour, Month, Year (from Order Date)
3. City (from Purchase Address)
4. Quarter (from Month)

# Visual Analysis
One of the purposes of visual analysis is to create a summary for the important facts found in a dataset. It is much easier to read and understand a well visualized data than trying to read a raw dataset with multiple columns and rows. The aims of this project was achieved with the help of visualizations in the form of bar charts and line plots.

# Findings
1. 2019 had the highest sales revenue ($ 34,456,867.65) as compared to 2020 with ($ 8,670.29) and this was due to the inavalability of the entire sales transactions of 2020(Only January was available).
2. December, October and October were the top 3 selling months with a sales revenue of ($4,608,295.70 ,$3,734,777.86 , $3,389,217.98 respectively)
3. San Francisco (CA) $8,254,743.55 , Los Angeles (CA)	$5,448,304.28 , and New York City (NY) $4,661,867.14 were the top 3 cities with high sales revenue generation.
4. The 4th quarter of the year generated the highest sales revenue $11,540,948.61


# Conclusion
The downside of this analysis is that there was no enough data for the year 2020. This prevented the possibilities of making a more indepth analysis for comparism. With such little information, it will be difficult to make well informed decisions that will help to improve the business.
   
Thanks for reading.
Suggestions and Reccomendations are warmly welcomed.
