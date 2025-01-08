# Online-Shopping-Analysis
Online Shopping Analysis using SQL

## **📖 About the Project**

This project, is analysis of a customer and order dataset to uncover business insights and demonstrate SQL skills. The analysis focuses on understanding customer behavior, product performance, and order patterns. The project highlights various SQL techniques such as joins, aggregation, subqueries, and window functions.

---

## **💡 Objectives**

1. Identify top-performing customers and products.
2. Understand trends in order frequency and spending.
3. Analyze product popularity and categories.
4. Demonstrate proficiency in SQL through complex queries.

---

## **📊 Dataset Overview**

The dataset consists of the following tables:

1. **Customers** (CustomerID, CustomerName, ContactName, Address, City, PostalCode, Country)
2. **Categories** (CategoryID,CategoryName, Description)
3. **Employees** (EmployeeID, LastName, FirstName, BirthDate, Photo, Notes)
4. **OrderDetails** (OrderDetailID, OrderID, ProductID, Quantity)
5. **Orders** (OrderID, CustomerID, EmployeeID, OrderDate, ShipperID)
6. **Products** (ProductID, ProductName, SupplierID, CategoryID, Unit, Price)
7. **Shippers** (ShipperID, ShipperName, Phone)

---

## **🔍 Analysis Highlights**

### 1. **Customer Insights**
- Identified top customers by the number of orders and total spending.
- Analyzed customers who have not placed any orders yet.

### 2. **Order Insights**
- Calculated total revenue per order.
- Identified trends in high-value orders.

### 3. **Product Insights**
- Ranked the most and least expensive products.
- Identified products that no one bought.
- Mapped products to their categories.

### 4. **Shipping Insights**
- Analyzed total revenue associated with each shipping company.

---

# **📂 Key SQL Queries**

## Q1. Select customer name together with each order the customer made.


## Q2. Select order id together with name of employee who handled the order.


## Q3. Select customers who did not placed any order yet.


## Q4. Select order id together with the name of products.


## Q5. Select products that no one bought.


## Q6. Select customer together with the products that he bought.

## Q7. Select product names together with the name of corresponding category.
 

## Q8. Select orders together with the name of the shipping company.
 
## Q9. Select customers with id greater than 50 together with each order they made.
 

## Q10. Select employees together with orders with order id greater than 10400.
 


## Q11. Select the most expensive product.
 
## Q12. Select the second most expensive product.
 

## Q13. Select name and price of each product, sort the result by price in decreasing order.
 

## Q14. Select 5 most expensive products.
 

## Q15. Select 5 most expensive products without the most expensive (in final 4 products).
 

## Q16. Select name of the cheapest product (only name) without using LIMIT and OFFSET.
 


## Q17. Select name of the cheapest product (only name) using subquery.
 

## Q18. Select number of employees with LastName that starts with 'D'.
 

## Q19. BONUS : same question for Customer this time.
 

## Q20. Select customer name together with the number of orders made by the corresponding customer 
sort the result by number of orders in decreasing order.
 

## Q21. Add up the price of all products.
 

## Q22. Select orderID together with the total price of  that Order, order the result by total price of order in increasing order.
 
## Q23. Select customer who spend the most money.
 
## Q24. Select customer who spend the most money and lives in Canada.
 

## Q25. Select customer who spend the second most money.
 

## Q26. Select shipper together with the total price of proceed orders.
 





## **🚀 Results **
### Insights Gained:
The top customer contributed 15% of the total revenue.
10% of products remained unsold.
The majority of high-value orders were handled by a specific shipping company.
