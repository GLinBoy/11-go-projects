## Golang With MYSQL Book Management System

### CURL commands:

- Get all the books
  - `curl --location --request GET 'localhost:9010/book/'`
- Get a book by ID
  - `curl --location --request GET 'localhost:9010/book/1'`
- Create a new book
  - `curl --location --request POST 'localhost:9010/book/' --header 'Content-Type: application/json' --data-raw '{"Name":"The Startup way", "Author": "Eric Rises", "Publication": "Penguin"}'`
- Update a book
  - `curl --location --request PUT 'localhost:9010/book/2' --header 'Content-Type: application/json' --data-raw '{"Name":"The Startup way", "Author": "Eric Rises", "Publication": "Orion"}'`
- Delete a book
  - `curl --location --request DELETE 'localhost:9010/book/2'`
