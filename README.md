# Python-SQL-EcommerceAnalysis
mm
# Ecommerce Data Analysis Project

## Project Overview
This project involves an in-depth analysis of an e-commerce dataset using Python and SQL. The primary goal is to extract valuable insights related to customer behavior, sales performance, and order fulfillment processes. The analysis focuses on various aspects such as sales trends, customer distribution, and payment methods, providing a comprehensive understanding of the e-commerce operations.

## Datasets Used
The project utilizes seven key datasets:

- **customers.csv**
  - Columns: `customer_id`, `customer_unique_id`, `customer_zip_code_prefix`, `customer_city`, `customer_state`
  
- **geolocations.csv**
  - Columns: `geolocation_zip_code_prefix`, `geolocation_lat`, `geolocation_lng`, `geolocation_city`, `geolocation_state`
  
- **order_items.csv**
  - Columns: `order_id`, `order_item_id`, `product_id`, `seller_id`, `shipping_limit_date`, `price`, `freight_value`
  
- **orders.csv**
  - Columns: `order_id`, `customer_id`, `order_status`, `order_purchase_timestamp`, `order_delivered_carrier_date`, `order_delivered_customer_date`, `order_estimated_delivery_date`
  
- **payments.csv**
  - Columns: `order_id`, `payment_sequential`, `payment_type`, `payment_installments`, `payment_value`
  
- **products.csv**
  - Columns: `product_id`, `product_category_name`, `product_name_length`, `product_description_length`, `product_photos_qty`, `product_weight_g`, `product_length_cm`, `product_height_cm`, `product_width_cm`
  
- **sellers.csv**
  - Columns: `seller_id`, `seller_zip_code_prefix`, `seller_city`, `seller_state`

## Tools and Libraries Used
- **Python**: Used for data manipulation and analysis.
- **Pandas**: For handling and processing the data.
- **SQL**: Integrated with Python for querying and analyzing the dataset.
- **MySQL Connector**: For connecting Python to the MySQL database.
- **Seaborn**: For data visualization and statistical plotting.
- **Matplotlib**: For creating static, and interactive visualizations in Python.

## Project Structure
The analysis is organized into several key sections:

### Data Loading and Preprocessing:
- CSV files are read and cleaned to prepare for analysis. Missing values are handled appropriately, and data types are set for SQL compatibility.

### SQL Queries:
- Various SQL queries are executed to extract insights from the datasets. These include:
  - Counting the number of orders placed in 2017.
  - Calculating total sales per product category.
  - Analyzing payment methods and installment usage.
  - Exploring customer distribution across different cities and states.

### Insights:
- The analysis reveals important business insights, such as:
  - Which product categories generate the most revenue.
  - The proportion of customers paying in installments.
  - Key trends in customer orders and delivery times.

## Conclusion
This project provides a detailed analysis of e-commerce operations, uncovering trends and patterns that can help improve business strategies. The combination of Python and SQL allows for efficient data processing and insightful querying, making this a robust data analysis project.
