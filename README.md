# CUSTOMERS-DASHBOARD-using-TABLEAU

## MAKING IT DYNAMIC TO FILTERS AND ALSO ADDING BUTTONS TO SWITCH FROM CUSTOMERS DASHBOARD TO SALES DASHBOARD AND VICE_VERSA.


# CUSTOMER-DASHBOARD

## Table of Contents
- [Purpose](#purpose)
- [Build Data Source](#builddatasource)
- [Analysing Requirements and choosing right chart](#choosingrightchart)
- [Prerequisites](#Prerequisites)
- [Data Filters](#DataFilters)
- [Dashboard](#Dashboard)

### Making it dynamic and adding buttons to switch from ## SALES DASHBOARD to CUSTOMERS DASHBOARD.

## Purpose
To present an overview of CUSTOMER data, trends and behaviour to understand customer segments and improve customer satisfaction.
Building dashboard to help stakeholders, including salesmanager and executives to analyse Customers data respective to sales and profit and products bought.



## Build Data Source
- Connecting to sales data : orders.csv, customers.csv, location.csv, product.csv.
- Creating Data Model using Relationship between above files where orders will be fact and other files are dimension.
- Rename Fields and Tables.
- Check Data types.

## Analysing Requirements and choosing right chart

1. KPI OVERVIEW  [using KPI BANS]
   - Display summary of Total Customers, Sales per customers and Orders for current year and previous year.
     
2. SALES TRENDS [using SPARKLINE]
   - Present data for each KPI on monthly basis for CY and PY.
   - Identify months with highest and lowest number of customers, sales per customer, orders and make them easy to recognize respectively.
     
3. CUSTOMER DISTRIBUTIONS [Histogram]
   - Total number of orders for each customer for current year
   - Include LOD expression to get the results.

4. Top 10 customers. [TABLE]
     

## Prerequisites
Tableau Public, Interactive parameters, ,Adding Filter actions, navigate buttons

## Data Filters
 Allow users to filter data by product information(category, subcategory) and by Location info (region, state, city).
 
 
## Dashboard
![LINK to DASHBOARD](=https://public.tableau.com/views/CustomersDASHBOARD/CustomerDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

