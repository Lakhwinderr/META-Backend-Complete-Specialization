
# Creating Tables in a Database with SQL

## Introduction
- Building a database involves organizing and storing data effectively.
- SQL (Structured Query Language) allows you to create tables within a database to structure and manage your data.
- In this tutorial, we'll explore how to create tables in a database using SQL syntax.

## SQL Create Table Statement Syntax
- To create a table, use the `CREATE TABLE` statement with the following syntax:
  ```sql
  CREATE TABLE table_name (
      column1_name datatype,
      column2_name datatype,
      ...
  );
  ```
- `table_name`: Name of the table you want to create.
- `( )`: Parentheses used to define column names and their data types.
- `column_name`: Name of each column within the table.
- `datatype`: Specifies the type of data that can be stored in each column.

## Creating a Table
- Before creating tables, ensure you have an existing database on the server.
- Example: Creating a "Customers" table in the "Bookstore" database to store customer data.

```sql
CREATE TABLE customers (
    customer_name VARCHAR(255),
    phone_number INT
);
```

- `VARCHAR(255)`: Data type for the "customer_name" column, allowing various types of data.
- `INT`: Data type for the "phone_number" column, restricting it to whole numbers.

## Conclusion
- SQL provides a structured way to create tables in a database.
- Use the `CREATE TABLE` statement with the appropriate column names and data types to define the table's structure.
- Organizing data in tables is essential for effective data management in database systems.
