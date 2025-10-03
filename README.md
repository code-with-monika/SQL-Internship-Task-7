## Task 7 – Creating Views in SQL
##  Objective

The objective of this task is to learn how to create and use Views in SQL for data abstraction, security, and simplifying complex queries.

## What is a View?

A view is a virtual table created using a SQL SELECT statement.

It does not store data physically like a table, but shows data from existing tables.

It is mainly used for data abstraction, security, and reusability.

A view can include specific columns, rows, or results of joins and aggregations.


## Why Use Views?

Data Abstraction – Hide unnecessary details and show only required data.

Security – Restrict access to sensitive columns (like salary, personal info).

Reusability – Reuse complex queries multiple times without rewriting them.

Simplicity – Simplify queries by encapsulating joins and conditions.

Consistency – Ensure the same logic is applied everywhere when reused.

## Key Features of Views

Views are virtual – they don’t store data, only the query.

Some views are updatable, meaning you can insert, update, or delete data through them.

Complex views (with joins, aggregations) are usually read-only.

A view can be used just like a table in queries.

You can drop a view anytime without affecting the base tables.

