# Day 49

## In a SQL table, what is the difference between information in a row and information in a column?
Column information is a single value. Row information is a collection of column information.

## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.
CREATE TABLE characters
(
  id INT NOT NULL AUTO_INCREMENT,
  name VARCHAR(100),
  age VHARCHAR(50),
  description VARCHAR(200),
  PRIMARY KEY (id)
)

## What is the difference between the following statements: DELETE FROM table_name; DROP TABLE table_name;
DELETE clears out a table but leaves the table intact. DROP TABLE removes the table from the db completely.