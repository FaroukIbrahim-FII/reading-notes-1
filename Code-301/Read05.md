# Read: Class 05

## How would you break a mock into a component heirarchy?

* By drawing boxes around every component (and subcomponent) in the mock and give them all names.

## What is the single responsibility principle and how does it apply to components?

* use single responsibility principle : (SRP) is a computer-programming principle that states that every module, class or function in a computer program should have responsibility over a single part of that program's functionality, and it should encapsulate that part. All of that module, class or function's services should be narrowly aligned with that responsibility.

## What does it mean to build a ‘static’ version of your application?

* build a version that takes your data model and renders the UI but has no interactivity. It’s best to decouple these processes because building a static version requires a lot of typing and no thinking, and adding interactivity requires a lot of thinking and not a lot of typing.

## Once you have a static application, what do you need to add?

* You need to add states.

## What are the three questions you can ask to determine if something is state?

* Is it passed in from a parent via props?
* Does it remain unchanged over time?
* Can you compute it based on any other state or props in your component?

## How can you identify where state needs to live?

* Either the common owner or another component higher up in the hierarchy should own the state.
