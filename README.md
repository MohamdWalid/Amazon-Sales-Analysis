## =>This project is for analyzing the sales of Amazon. The goal of this project is to show some KPIS and answer some questions that will benefit the business.

## =>Data
     We have 12 files, each of which contains sales for a month  
     in the year 2019.
    1) Order ID: it is an ID for each Product
    2) Product: it is a Product Name
    3) Quantity Ordered: Quantity of product ordered
    4) Price Each: It's the price per piece
    5) Order Date: Date of order
    6) Purchase Address: Customer address

## =>Questions
   1) What was the best month for sales? How much was earned that 
       month?
   2) What city sold the most product?
   3) What city sold the most Sales?
   4) What time should we display advertisements to maximize the 
        likelihood of customer’s buying product?


## =>Data Preparing
   1) We can concat all sales files in one excel file.
   2) Drop Duplicated Rows
   3) There is missing values in one row, we can drop it
   4) Covert each column to suitable data type
   5) ADD Column Sales by multiply Quantity Ordered and Price Each
   6) ADD Columns time, Day, month by extract them from Order Date 
       column
   7) Drop Order Date column
   8) ADD City Column by extract it from Purchase Address
  
## =>Insights
   1) the best sales in December Month
   2) The city that buys the most products is San Francisco.
   3) The best time to advertise our new products is from 10 AM to 8 PM 
        because this is the time when most purchases are made






