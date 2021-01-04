# Day 16

## What are some signs and causes of callback hell?
Callback hell comes from when javascript is written in way where execution happens visually from top to bottom. The code looks messy and is hard to read in general.

## What does asynchronus mean and how are callbacks involved?
Asynchronus in this context means something that will happen in the future, independent of the main thread. Functions that use callbacks are asynchronus.

## Summarize three ways to avoid/fix callback hell.
Keep your code shallow by naming your functions and moving them to the top level.
Modularize by splitting code into multiple files and import them.
Handle your errors. The first argument in node.js is the error

https://timzaleski.github.io/triviaapi/