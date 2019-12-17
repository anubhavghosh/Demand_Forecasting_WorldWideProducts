# Demand Forecasting WorldWideProducts
Demand Forecasting of a product using Time Series Forecasting and Analysis

# Case Type: B2B Demand forecasting of a particular product
## Use and context of the data
The dataset contains historical product demand for a manufacturing company with footprints globally. The company provides thousands of products within dozens of product categories. There are four central warehouses to ship products within the region it is responsible for. Since the products are manufactured in different locations all over the world, it normally takes more than one month to ship products via ocean to different central warehouses. If forecasts for each product in different central with reasonable accuracy for the monthly demand for month after next can be achieved, it would be beneficial to the company in multiple ways.

## Source of Data: 
https://www.kaggle.com/felixzhao/productdemandforecasting 

## Project Requirements:
1. Set up a data science project structure in a new git repository in your GitHub account
2. Download the product demand data set from
https://www.kaggle.com/felixzhao/productdemandforecasting 
3. Load the data set into panda data frames
4. Formulate one or two ideas on how feature engineering would help the data set to establish additional value using exploratory data analysis
5. Build one or more forecasting models to determine the demand for a particular product using the other columns as features
6. Document your process and results
7. Commit your notebook, source code, visualizations and other supporting files to the git repository in GitHub

## Project Delivery Steps:
(For more information, please check the Jupyter notebook)
1. Import modules and data 
2. Count of Products by grouping
3. Select a product to work on this project
We will be working on demand forecasting of product 1359 as it has the highest count. There is no particular way of choosing a product and any of the above products can be worked upon for its demand forecasting.
4. Trim: We do not need the details of 'Warehouse', 'Product Code' and 'Product Category' for demand forecasting. All we need is the demand and time(date)
5. Creating the major axis-that is Time. All the data will now be indexed in terms of time.
6. Formatting
7. Determining Monthly Demand
Get the demand in terms of January, February.....December
8. Note that the sharp dip in 2017 is due to the data being incomplete in 2017
9. Create Train and Test Data
Last 10 months make up the test data
10. Find: Demand for product 1359
11. Simple Smoothing
12. Root mean square error calculation
13. Exponential Smoothing
Exponential smoothing uses the weighted average of previous observations where more weight is given to the most recent observations and the weight decreases as observations get older.
14. Root mean square error calculation
