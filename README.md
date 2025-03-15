# VEHICLES-SALES-POWER-BI-DATA-ANALYSIS

## Project Overview:
- This Power BI project focuses on analyzing sales performance, customer behavior, and financial transactions to drive data-driven decision-making.
- By integrating multiple datasets—including customers, orders, payments, and products—the project provides a comprehensive view of business operations.

## Dataset Information
Below is a list of all datasets along with their column names and descriptions:

## 1)Customers (customers.csv)

- customerNumber – Unique identifier for each customer
- customerName – Name of the customer
- contactLastName – Last name of the contact person
- contactFirstName – First name of the contact person
- phone – Contact phone number
- addressLine1, addressLine2 – Customer address details
- city, state, postalCode, country – Location details
- salesRepEmployeeNumber – Employee assigned as the sales representative
- creditLimit – Credit limit assigned to the customer

## 2)Employees (employees.csv)

- employeeNumber – Unique identifier for each employee
- lastName, firstName – Employee's name
- extension – Employee's extension number
- email – Contact email
- officeCode – Code representing the office location
- reportsTo – Employee’s manager ID
- jobTitle – Employee’s designation

## 3)Offices (offices.csv)

- officeCode – Unique identifier for the office
- city, state, country, postalCode – Location details
- phone – Office contact number
- addressLine1, addressLine2 – Office address details
- territory – Assigned sales territory

## 4)Order Details (order_details.csv)

- orderNumber – Order ID linked to the orders table
- productCode – Unique product identifier
- quantityOrdered – Number of units ordered
- priceEach – Price per unit
- orderLineNumber – Line item number for each order

## 5)Orders (orders.csv)

- orderNumber – Unique identifier for each order
- orderDate – Date when the order was placed
- requiredDate – Expected delivery date
- shippedDate – Date when the order was shipped
- status – Order status (e.g., Shipped, Pending, Canceled)
- comments – Additional comments
- customerNumber – Customer ID linked to the customer table

## 6)Payments (payments.csv)

- customerNumber – Customer ID linked to the customer table
- checkNumber – Unique transaction identifier
- paymentDate – Date of the payment
- amount – Payment amount

## 7)Product Lines (productlines.csv)

- productLine – Category of products
- textDescription – Short description of the product line

## 8)Products (products.csv)

- productCode – Unique identifier for each product
- productName – Name of the product
- productLine – Category to which the product belongs
- productVendor – Name of the vendor supplying the product
- productDescription – Detailed description of the product
- quantityInStock – Available stock quantity
- buyPrice – Purchase price
- MSRP – Manufacturer's Suggested Retail Price

## Key Steps & Implementation
- Data Preparation & Cleaning: Imported multiple datasets, handled missing values, and ensured data consistency using Power Query Editor.
- Data Modeling: Established relationships between key tables, enabling seamless analysis of sales, products, and customer interactions.
- DAX Measures & Calculations: Created key metrics such as total revenue, sales growth, top-selling products.
- Dashboard Development: Designed interactive visualizations to track sales performance, revenue distribution, and customer trends.

## Conclusion
- The Power BI dashboard provides a powerful tool for business intelligence, offering actionable insights to improve sales strategy, optimize customer engagement, and enhance revenue growth.
- By leveraging data visualization, the organization can make informed decisions, streamline operations, and boost overall performance.
  


