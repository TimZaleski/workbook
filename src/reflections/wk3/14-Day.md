# Day 14

## What problems does the Observer Pattern seek to solve?
If you want to project data to multiple page elements, it allows one-to-many data binding.

## What are the three mechanisms of the observer pattern?
The subscribe, unsubscribe, and and broadcast methods.

## Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.
We have these listeners that know when an event has been triggered. When the user needs to see a change based on an event, the Controller related to that event can update the HTML to reflect that change.