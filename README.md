## Ignite Node.js - 2nd Challenge - Working with middlewares

A simple backend application that enables users to create and check todos.

## Tools Utilized:
- Node.js
- Express

## Application Objective:
- Practice the creation and use of middlewares

## Requisites:
- Creation of a checksExistsUserAccount middleware. (This middleware searches the user by the username provided by the requisition headers, and if it is true, repasses the user to the request)
- Creation of a checksCreateTodosUserAvailability middleware. (This middleware checks if the user account is free or pro. If the account is free, it limits the todos quantity to ten)
- Creation of a checksTodoExists middleware. (This middleware validates the user, then checks if the todo id is a UUID and if it exists according to its id)
- Creation of a findUserById middleware. (This middleware is similar to the checksExistsUserAccount middleware, but it searches by the id within the route parameters)
