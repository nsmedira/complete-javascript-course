# Budget App

## What you will learn

- How to use the module pattern
- Private vs public data
- Encapsulation
- Separation of concerns

# Project Planning

- Add event handler
- Get input values
- Add the new item to our data structure
- Add the new item to the UI
- Calculate budget
- Update the UI

# Modules

- Encapsulate some data privately and expose other data publicly
- Keep units of code for a project cleanly separated and organized

## UI Module

- Get input values
- Add the new item to the UI
- Update the UI

## Data Module

- Add the new item to our data structure
- Calculate budget

## Controller Module

- Add even thandler

# Notes

## Immediately Invoked Function Expression

Allows us to have data privacy because it creates a new scope that is not available from the outside scope.

## Module pattern

A module should return an object that contains all the functions that we want available from the outside scope.

## Closures

An inner function always has access to its outer functions variables and functions, even after the outer function has returned.

## Separation of concerns

Each part of our application should be designed to perform only one task.