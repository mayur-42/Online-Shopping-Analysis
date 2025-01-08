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

## **📊 Tools & Technologies Used**

<img src="https://upload.wikimedia.org/wikipedia/labs/8/8e/Mysql_logo.png" alt="mysql-logo" width="200" height="100"/>

---

# **📂 Key SQL Queries**

## Q1. Select customer name together with each order the customer made.

![OUTPUT_Q1](https://github.com/user-attachments/assets/6982d1a7-5010-46e7-91bb-0f6c3c99dfe5)

## Q2. Select order id together with name of employee who handled the order.

![OUTPUT_Q2](https://github.com/user-attachments/assets/8479b45a-bc75-4833-b0e1-2c6a3c798f1b)

## Q3. Select customers who did not placed any order yet.

![OUTPUT_Q3](https://github.com/user-attachments/assets/5f1e88e9-8d7b-404e-980e-11d2932a4d86)


## Q4. Select order id together with the name of products.

![OUTPUT_Q4](https://github.com/user-attachments/assets/29cacfd3-fe62-42ef-8d47-ddf67005e30f)

## Q5. Select products that no one bought.

![OUTPUT_Q5](https://github.com/user-attachments/assets/27e91461-6de8-4714-99d6-cc18bb8f5954)

## Q6. Select customer together with the products that he bought.

![OUTPUT_Q6](https://github.com/user-attachments/assets/f05a2e0f-9324-4d4d-a914-598b6674ed01)

## Q7. Select product names together with the name of corresponding category.
 
![OUTPUT_Q7](https://github.com/user-attachments/assets/478ad0da-71f7-4906-b20d-5318ccd72707)

## Q8. Select orders together with the name of the shipping company.
 
 ![OUTPUT_Q8](https://github.com/user-attachments/assets/af8f06ff-c08c-401f-9fca-c6a357c54439)

## Q9. Select customers with id greater than 50 together with each order they made.
 
![OUTPUT_Q9](https://github.com/user-attachments/assets/f556aae3-889e-46b0-9b2c-f39feeec8c6c)

## Q10. Select employees together with orders with order id greater than 10400.
 
![OUTPUT_Q10](https://github.com/user-attachments/assets/2c3b761e-e4dc-4690-acad-09273f51798e)

## Q11. Select the most expensive product.
 
![OUTPUT_Q11](https://github.com/user-attachments/assets/85d77450-9bbf-4443-a999-1d4548cce4eb)

## Q12. Select the second most expensive product.
 
![OUTPUT_Q12](https://github.com/user-attachments/assets/ba62d585-5776-4e44-b00e-7f615c5256fe)

## Q13. Select name and price of each product, sort the result by price in decreasing order.
 
![OUTPUT_Q13](https://github.com/user-attachments/assets/81a3cecd-6e7b-42fc-a5b3-5b42e049e0b2)

## Q14. Select 5 most expensive products.
 
![OUTPUT_Q14](https://github.com/user-attachments/assets/52a6ce30-5c9a-41fa-9e30-074098bf748e)

## Q15. Select 5 most expensive products without the most expensive (in final 4 products).
 
![OUTPUT_Q15](https://github.com/user-attachments/assets/8c59a03c-f448-452a-beab-aa3cd23be88b)

## Q16. Select name of the cheapest product (only name) without using LIMIT and OFFSET.
 
![OUTPUT_Q16](https://github.com/user-attachments/assets/e6a0cdd4-a832-44cd-89b4-38b0da4536d1)

## Q17. Select name of the cheapest product (only name) using subquery.
 
![OUTPUT_Q17](https://github.com/user-attachments/assets/3f883bb0-62f1-4534-9a4e-94fa65e929ab)

## Q18. Select number of employees with LastName that starts with 'D'.
 
![OUTPUT_Q18](https://github.com/user-attachments/assets/fd8d622d-6d4c-494f-81e0-d8b5d8f8aff1)

## Q19. BONUS : same question for Customer this time.
 
![OUTPUT_Q19](https://github.com/user-attachments/assets/ca7eff5a-91fe-4c95-808c-65e2a159c46a)

## Q20. Select customer name together with the number of orders made by the corresponding customer sort the result by number of orders in decreasing order.
 
![OUTPUT_Q20](https://github.com/user-attachments/assets/ac72155c-8eab-4dd2-9eb7-9552453fc2b8)

## Q21. Add up the price of all products.

![OUTPUT_Q21](https://github.com/user-attachments/assets/402ff6ec-6978-4607-a6be-d5a72f3851de)

## Q22. Select orderID together with the total price of  that Order, order the result by total price of order in increasing order.

![OUTPUT_Q22](https://github.com/user-attachments/assets/0453c94a-d1f3-4cb6-814e-66c1b3cdbd38)

## Q23. Select customer who spend the most money.

![OUTPUT_Q23](https://github.com/user-attachments/assets/685df78d-323a-477d-b26c-d476cae8ee04)

## Q24. Select customer who spend the most money and lives in Canada.
 
![OUTPUT_Q24](https://github.com/user-attachments/assets/9bf65ddb-b8f4-48e7-ae01-9f94fb261e03)

## Q25. Select customer who spend the second most money.
 
![OUTPUT_Q25](https://github.com/user-attachments/assets/5a38dda8-732e-4990-a115-916d266f68a4)

## Q26. Select shipper together with the total price of proceed orders.
 
![OUTPUT_Q26](https://github.com/user-attachments/assets/07913f51-50f9-460e-812f-efb48fbf9d23)


# 🚀 Results 
## Insights Gained:
The top customer contributed 15% of the total revenue.
10% of products remained unsold.
The majority of high-value orders were handled by a specific shipping company.
