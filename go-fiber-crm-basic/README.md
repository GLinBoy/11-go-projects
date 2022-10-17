## CRM with Golang Fiber

### CURL commands:

- Get all the leads
  - `curl --location --request GET 'localhost:3000/api/v1/lead'`
- Get a lead by ID
  - `curl --location --request GET 'localhost:3000/api/v1/lead/1'`
- Create a new book
  - `curl --location --request POST 'localhost:3000/api/v1/lead' --header 'Content-Type: application/json' --data-raw '{"name": "Test", "company": "Test Company", "email": "info@test-company.co", "phone": 123456789}'`
- Delete a book
  - `curl --location --request DELETE 'localhost:3000/api/v1/lead/2'`
