## 🛠️ Practical Task – Build a REST API

Create a simple Book Management API using Express.js and Node.js

### Requirements:

- Set up a basic Express.js server with routing.

- Create the following endpoints:
  - `GET /books` – Fetch all books.
  - `GET /books/:id` – Get book by ID.
  - `POST /books` – Add a new book.
  - `PUT /books/:id` – Update a book.
  - `DELETE /books/:id` – Delete a book.

- Use an in-memory array or JSON file as a mock database (MongoDB optional).

- Validate that `title` and `author` are required in `POST` and `PUT`.

- Implement basic error handling with proper status codes.

- Organize code into at least 2 files: `server.js` and `routes/books.js`.

- **BONUS**: Implement simple pagination for `GET /books?page=1&limit=10`.


## ✅ Submission Guidelines:
Submit your code as a GitHub repo or ZIP file.
Include a README with setup instructions and sample test data.
