# project5
Data set used: https://www.kaggle.com/felixzhao/productdemandforecasting
This dataset contains data regarding order demands from four different warehouses over a period of four years from 2012 to 2016. The columns in this data set are as follows:
Date: Date when the product was ordered from 2012 to 2016
Product code: Unique product code every product is associated with
Warehouse: Warehouse which the product is a part of
Product_Category. The category in which the product belongs
Order_Demand: The number of items for which the order was placed

1.	Data Cleaning

    Loaded the dataset Historical Product Demand.csv using pandas library
    
    Performed data cleaning in data and removed the redundant records and null records and described the dataset
    
2.	Data Transformation

    Modified the data type of ‘Date’ column from string to date and set it as an index for pandas to treat it as a date.

    Created a subset of the dataset for products- product_0082 and product_0002.

3.	Data Analysis

    Analyzed the data and converted ‘date’ column to date datatype.
    
    Noted that that there are 427 unique items in Warehouse A, 244 unique items in Warehouse C, 1625 items in Warehouse J and 553 unique items in Warehouse S
    
    Created new data frames by selecting products 'Product_0082' and 'Product_0002' and observed the order demands over the months and years. Analyzed the number of matches         played in each league in each season.
    
    Calculated a monthly mean of the product demand with product id '82' and plotted a graph of the order demand. Noted that the order demand has increased over the months.
    
    Verified that the data is stationary and p-value is very small i.e. of the order of  10-7

    Performed time series forecasting using two models- Linear regression and ARIMA model. Noted that ARIMA model gave better prediction results. Used ARIMA model to predict
    
4.	Data Plotting
 
    Plotted all the predicted data as per regression model and ARIMA model using a line graph.
    
    Plotted the future prediction of the model and noted that demand for the order increased for the next 30 days.
    
    Plotted a graph of monthly and yearly order demands for two products.
    
5.	Conclusion/Inferences

    Noted that the order demand for Product 82 has increased over the months and has been increasing. 
    
    The future prediction of the product demand also states that there is an exponential increase in the product demand beginning with around 10000 orders in the beginning of       December 2016. The demand raises to 18000 towards the end of the month.
