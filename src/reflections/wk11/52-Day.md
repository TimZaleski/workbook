# Day 52

## What is the difference between a primary key and a foreign key?
A primary key of a table is the key of that table. A foreign key present in a table represents a relationship to a row in another table.

## What is an Alias?
An alias can be declared after the first instance of the table name in a query. It can be substituted for the full name of the table.

## Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:
SELECT p.*
FROM doctorpatients dp
JOIN patients p ON p.id = dp.patientId
WHERE dp.doctorId = xyz

https://github.com/TimZaleski/jobapi