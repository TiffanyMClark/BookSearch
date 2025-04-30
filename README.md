# BookSearch


This is a full-stack application that allows users to search for books.
The back-end is powered by a GraphQL API using Apollo Server, while the front-end uses REACT.


## Features

 Users can search for books
Users can sign up, log in to their account
users can save or remove books from their account

## Installation
Node.js newest versions of each please!
MongoDB 
npm or yarn whatever you prefer to use
and the npm i for everything else

Queries & Mutations:
Queries:
me: Fetches the current user's data.
Mutations:
login(email: String!, password: String!): Logs the user and returns a JWT token and data.

addUser(username: String!, email: String!, password: String!): Registers a new user and returns a JWT token and user data.

saveBook(bookId: String!, authors: [String]!, description: String, title: String!, image: String, link: String): Saves a book to the user's account.

removeBook(bookId: String!): Removes a book from the saved books list.

[https://helpful-genie-9f0d34.netlify.app/](https://booksearch-5pmr.onrender.com/)
