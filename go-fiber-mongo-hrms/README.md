## HRMS with Golang Fiber

### CURL commands:

- Get all the employees
  - `curl --location --request GET 'localhost:3000/employee'`
- Create a new employee
  - `curl --location --request POST 'localhost:3000/employee' --header 'Content-Type: application/json' --data-raw '{ "name": "rupert", "salary": 3424, "age": 24}'`
- Update an employee
  - `curl --location --request PUT 'localhost:3000/employee/634e7ab2ba0c4623f33d795b' --header 'Content-Type: application/json' --data-raw '{ "id": "634e7ab2ba0c4623f33d795b", "name": "edited rupert", "salary": 3000.00, "age": 36 }'`
- Delete an employee
  - `curl --location --request DELETE 'localhost:3000/employee/634e7aa6ba0c4623f33d795a'`
