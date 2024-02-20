Book Management System Challenge

Introduction
You are tasked with creating a simple book management system using Express.js, Axios, JSON-server, and EJS templating engine. This challenge will test your ability to implement CRUD (Create, Read, Update, Delete) operations on a collection of books stored in a JSON file using RESTful API endpoints.

Requirements
Implement a backend server using Express.js.
Utilize JSON-server to simulate a RESTful API for managing books.
Create an EJS template for rendering views.
Implement CRUD endpoints for managing books.
Ensure proper error handling and validation.
Write clear and concise code with appropriate comments.
Instructions
Clone this repository to your local machine.

bash
Copy code
git clone https://github.com/your-username/book-management-challenge.git
Install dependencies using npm.

bash
Copy code
npm install
Start the JSON-server to simulate the backend.

bash
Copy code
npm run json-server
Start the Express server.

bash
Copy code
npm start
Access the application in your browser at http://localhost:3000.

Endpoints
GET /books: Retrieve all books.
GET /books/:id: Retrieve a specific book by ID.
POST /books: Create a new book.
PUT /books/:id: Update a book by ID.
DELETE /books/:id: Delete a book by ID.
JSON Data Structure
Each book object should have the following properties:
id (unique identifier)
title (title of the book)
author (author of the book)
genre (genre of the book)
year (publication year of the book)
Example of a book object:

json
Copy code
{
  "id": 1,
  "title": "To Kill a Mockingbird",
  "author": "Harper Lee",
  "genre": "Fiction",
  "year": 1960
}
Submission
Implement the required functionality according to the specifications above.
Commit your changes and push them to your GitHub repository.
Include a README.md file with clear instructions on how to run the application and details about the implemented endpoints.
Submit the GitHub repository link to your project.
Additional Notes
You can use any additional libraries or tools if necessary.
Make sure to handle edge cases such as invalid input and missing data gracefully.
Write clean, readable, and well-organized code.
Test your endpoints using tools like Postman or cURL to ensure they function correctly.
Feel free to ask for clarification if any part of the challenge is unclear.
