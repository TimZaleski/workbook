# Day 53

## What is SQL injection?
SQL injection is a method of attack that gives someone control over a database. It involves injecting SQL through user input queries.

## What are 3 methods SQL injection can be done by?
The first method is from unsanitized user input. The second is by modifying cookies to run SQL in the database. The third is having server variables like http headers contain SQL to be ran.

## How can we detect and sanitize SQL injection attacks?
You can dectect attacks with a web application firewall or an intrustion detection system. Using parameterized queries will prevent SQL injection.

https://github.com/TimZaleski/jobapi