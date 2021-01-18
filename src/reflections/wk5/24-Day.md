# Day 24

## What is a virtual property?
They are additional fields in models. You can set their value manually or automatically. These properties are not stored in MongoDB. They are generally computed properties.

## When might you use a virtual property?
A virtual property can be used when you don't want to persist a property in the database. They generally do some process that saves you from repeating code.

## How do you search by a virtual property's value?
Virtual properties aren't available for document queries, so you can't. Only non-virtual properties can be queried.

HACKATHON