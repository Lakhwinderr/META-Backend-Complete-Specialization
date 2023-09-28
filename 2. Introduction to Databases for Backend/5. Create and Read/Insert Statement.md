# Inserting Data into Database Tables with SQL

## Introduction
- In database management, you often need to add new rows of data to existing tables or create new tables.
- SQL provides the `INSERT` statement to quickly perform these tasks.
- By the end of this video, you'll understand the SQL syntax for inserting data into tables.

## SQL `INSERT INTO` Syntax
- To write an `INSERT` statement:
  - Start with `INSERT INTO` followed by the table name.
  - Specify the columns within parentheses, separated by commas.
  - Use the `VALUES` keyword and provide corresponding values in parentheses.
- Ensure the order of values matches the order of columns, and use quotation marks for non-numeric values.

```sql
-- Inserting a Single Record for Yuval
INSERT INTO Players (ID, Name, Age, StartDate)
VALUES (1, 'Yuval', 25, '2020-10-15');

-- Inserting Multiple Records for Mark and Karl
INSERT INTO Players (ID, Name, Age, StartDate)
VALUES
    (2, 'Mark', 27, '2020-10-12'),
    (3, 'Karl', 26, '2020-10-07');

```

## Retrieving Data
- You can use SQL queries to retrieve data from tables.
- Example query to select all columns from the "Players" table:
  ```sql
  SELECT * FROM Players;
