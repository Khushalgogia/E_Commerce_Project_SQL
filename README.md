# E-Commerce Project

### Objective:
1.	Explore the structure of the dataset by understanding the relationships between tables.
2.	Formulate SQL queries to extract meaningful insights from the data.

```
select * from list_of_orders
```

![Alt text](image.png)

```
select * from order_details
```

![Alt text](image-1.png)

```
select * from sales_target
```

![Alt text](image-2.png)


#### Analysis
1. Order_id is common in list_of_orders and order_details
2. Category is common in order_details and sales_target


#### Basic Queries:
1. Count of rows in each table

```
SELECT 'list_of_orders' AS Table_Name, COUNT(*) AS RowCount FROM list_of_orders
UNION
SELECT 'order_details' AS order_details, COUNT(*) AS RowCount FROM order_details
UNION
SELECT 'sales_target' AS sales_target, COUNT(*) AS RowCount FROM sales_target;
```
![Alt text](image-3.png)












