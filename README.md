This Microsoft Access database helps Sports Power Ltd., an online sporting goods supplier, manage customers, products, orders, and shipping details. The database includes tables, queries, and reports designed to track sales, calculate totals, and provide actionable insights into order management.

- Features
Tables

Shipping Details Table:

Fields: Tracking Code, Shipping Date, Courier Company, Left Warehouse?

Data types selected to match appropriate formats (Text, Date/Time, Yes/No).

Default value for Courier Company set as “Courier Post”.

Primary Key applied to ensure unique records.

- Queries

Total Cricket Bat Sales Query:

Returns only products named “Cricket Bat”.

Fields included: Product Name, Quantity, Total Price (calculated as Price × Quantity).

Totals applied:

Product Name: Grouped

Quantity: Sum

Total Price: Sum

- Reports

Online Sales Report:

Based on the Sales Report query.

Includes all fields from the Sales Report query.

Grouped by Customer Name.

Sorted by Order ID in descending order.

Layout: Stepped, Orientation: Portrait.

Title: Online Sales Report (Italicized).

Group Footer displays Total Order Amount per customer, formatted in Currency.

- Skills Demonstrated

Creating and modifying tables with primary keys, default values, and proper data types.

Building queries with calculated fields and selection criteria.

Applying totals and grouping in queries.

Designing professional reports with grouping, sorting, and formatting.

- Usage

Open the database file in Microsoft Access (2016 or later recommended).

Explore the Shipping Details table to track orders and shipping information.

Run the Total Cricket Bat Sales query to view sales summary of cricket bats.

Open the Online Sales Report to review customer order summaries with totals.

License

This repository is for educational purposes only.
