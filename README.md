SuperStore Sales Analysis Project
Objective : 
This project aims to use business intelligence tool to analyse the performance of a global superstore. The outcome of this analysis will assist stakeholders in making educated decisions about how to attain their goals.

DATA SOURCE:
This project’s data is open source, it is the Global Superstore dataset obtained from Kaggle. 

BI QUESTIONS:
This project focuses on descriptive and predictive analytics using the available historical data. The following questions will be addressed through the analysis:
The sales trend obtained via region?
The total count of sales and quantity?
The average delivery day required to perform a delivery?
The top 5 customers?
The sales trend in terms of market and segment?
The top 5 profitable products and the top 5 loss making products?

DATA CLEANING AND TRANSFORMATION:
To prepare the data for analysis, several pre-processing steps were performed using Power Query. These steps include removing null values, handling errors, changing data types, performing timeline checks, and creating new columns. The data was cleaned and transformed to ensure its suitability for analysis.


Removing Null values: The postal code column contained 81% missing data; as the column would not contribute to the analysis, it was deleted.


Handling Errors: During the investigation, it was observed that "Canada" appears in the region column. This was modified to read "North America." This problem was resolved using the find-and-replace technique.

Changing Data Types: Since the values are monetary, the data type for the sales, profit and shipping cost was changed from a decimal number to a fixed decimal number.

Timeline Check/ Data Range: The ship date and order date were sorted in descending order to ensure that there were no outliers in the dates. Both columns were discovered to be within the appropriate range as shown below.

Creating New Column: Subtracting the order date column from the ship date column yielded the shipment time column. It is essential to know how long the products will take to ship. The new column's data type was changed to a whole number and its order on the table was rearranged as shown below.
	
DATA ANALYSIS AND DASHBOARD:
The data analysis was divided into sales performance analysis, product analysis, customer analysis, and region analysis. Using DAX and calculated columns, these analyses provided insights into various aspects of the superstore's operations. Each segment has a dedicated dashboard page that addresses the business intelligence questions raised. The interactive dashboard allows users to navigate and personalize the displayed information according to their specific needs.

SUMMARY OF FINDINGS:
The total sales was found to be $13 Million and the average delivery day was estimated as 4.
Europe has the highest market sales of $4M followed by Asia Pacific with $3.29 M
Segment-wise, Consumer has the highest sales followed by Corporate Sales.
The most profitable product was found to be Canon Image and the loss making product was found to be Bevis round.

     
CONCLUSION:
In conclusion, this project utilized data analytics techniques to analyze the performance of a global superstore. Through the interactive dashboard and data insights, stakeholders can make informed decisions and take necessary actions to achieve their strategic objectives. By leveraging the power of data, businesses can drive growth, improve profitability, and stay competitive in today's dynamic market.


