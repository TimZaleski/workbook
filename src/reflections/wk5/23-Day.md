# Day 23

## In simple terms, what is a sub-document?
A sub-document is a document that is nested in another document. They are distinguishable by having a schema inside of another schema.

## When might you use a sub-document?
When you want to store an object inside of another object in MongoDB. It's generally easier to access and handle data if it will always belong to a single parent document, instead of having to fetch/request it by some ID.

## How do you add to a collection of sub-documents? What about editing them?
You can use "findOne" to get the document. Then you get, change and save the array. If you want to edit a single sub-document, just access it like every other object.

https://github.com/TimZaleski/planets