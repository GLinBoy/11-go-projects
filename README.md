## 11 Go Projects

This project is based on an online YouTube tutorial to create 11 projects with Go lang.

The video is available at [https://www.youtube.com/watch?v=jFfo23yIWac](https://www.youtube.com/watch?v=jFfo23yIWac)

⭐️ Course Contents ⭐️

- [x] ⌨️ ([0:00:00](https://www.youtube.com/watch?v=jFfo23yIWac&t=0s)) Build A Simple Web Server With Golang ([go-server](go-server/))
- [x] ⌨️ ([0:20:34](https://www.youtube.com/watch?v=jFfo23yIWac&t=1234s)) Build A CRUD API With Golang ([go-movies-crud](go-movies-crud/))
- [x] ⌨️ ([1:07:14](https://www.youtube.com/watch?v=jFfo23yIWac&t=4034s)) Golang With MYSQL Book Management System ([go-bookstore](go-bookstore/))
- [x] ⌨️ ([2:30:57](https://www.youtube.com/watch?v=jFfo23yIWac&t=9057s)) Simple SlackBot To Calculate Age ([slack-age-bot](slack-age-bot/))
- [x] ⌨️ ([2:44:12](https://www.youtube.com/watch?v=jFfo23yIWac&t=9852s)) Golang SlackBot for File Uploading ([slack-file-bot](slack-file-bot/))
- [x] ⌨️ ([3:01:45](https://www.youtube.com/watch?v=jFfo23yIWac&t=10905s)) Email Verifier Tool With Golang ([email-checker-tool](email-checker-tool/))
- [ ] ⌨️ ([3:24:32](https://www.youtube.com/watch?v=jFfo23yIWac&t=12272s)) AWS Lambda With Golang
- [ ] ⌨️ ([3:50:12](https://www.youtube.com/watch?v=jFfo23yIWac&t=13812s)) CRM with Golang Fiber
- [ ] ⌨️ ([4:34:34](https://www.youtube.com/watch?v=jFfo23yIWac&t=16474s)) HRMS with Golang Fiber
- [ ] ⌨️ ([5:44:25](https://www.youtube.com/watch?v=jFfo23yIWac&t=20665s)) Complete serverless stack with Golang
- [ ] ⌨️ ([7:28:55](https://www.youtube.com/watch?v=jFfo23yIWac&t=26935s)) A.I Bot with wolfram, wit.ai and Golang

---

### Golang With MYSQL Book Management System

#### CURL commands:

- Get all the books
  - `curl --location --request GET ‘localhost:9010/book/’`
- Get a book by ID
  - `curl --location --request GET ‘localhost:9010/book/1’`
- Create a new book
  - `curl --location --request POST 'localhost:9010/book/' --header 'Content-Type: application/json' --data-raw ‘{"Name":"The Startup way", "Author": "Eric Rises", "Publication": "Penguin"}’`
- Update a book
  - `curl --location --request PUT 'localhost:9010/book/2' --header 'Content-Type: application/json' --data-raw ‘{"Name":"The Startup way", "Author": "Eric Rises", "Publication": "Orion"}’`
- Delete a book
  - `curl --location --request DELETE 'localhost:9010/book/2'`
