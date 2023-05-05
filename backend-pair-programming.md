# Backend pair programming exercise

## Summary
In this exercise, we will implement a simple library management API using typescript and express.js.
In the final product, we want to manage a simple library system by manually invoking the system’s endpoints.

### Part 1
Build a simple REST API with a user and book resource. We want to add, find, update, and delete users and books via the API. 

### Part 2
We want to check out books, check the status of a book and check which books a specific user has checked out, via the API.

### Part 3 (bonus)
Given that we can have multiple copies of the same book, create a logic that will check for a given book's availability before
the user is able to check it out.

### Specs
- Create a typescript with express.js boilerplate
- Create a DB of your preference
- Connect the express.js server with the DB you've chosen
- Create a `user` resource
- Create a `book` resource
- Add Create, Read, Update and Delete endpoints for both resources
- In addition to the resource endpoints, implement three additional endpoints:
  - Allow a user to check out a book
  - Check which books a specific user has checked out
  - Check the current status of a particular book
- Create a small README/comment text file with the data modeling you used for the resources
