# Day 22

## What are the three types of relationships?
The three types of relationships are One-to-one, One-to-many, and Many-to-many.
Examples:
1:1 Each class has one teacher, and that teacher is assigned to only one class.
1:M Each student has multiple assignments, but those assignments have only one author.
M:N Each student has multiple classes, and each class has multiple students.

## What are the benefits of the traditional linking of relationships instead of embedding?
With linking on a foreign key, you don't increase the size of the original document. The results are also easier to parse.

## What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?
The relationship balance of your data determines which model to use. IE If you're working with a value that has a small amount of possibilities, one way embedding makes sense because you reduce the document size. 


https://github.com/TimZaleski/gregslistServer