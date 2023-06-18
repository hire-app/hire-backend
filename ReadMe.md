```markdown
# Backend

This is the backend for the user CRUD application. It provides a RESTful API for managing user data.

## Prerequisites

Before running the backend, ensure you have the following installed:

- Node.js
- MongoDB

## Getting Started

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the backend directory:

   ```bash
   cd backend
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the MongoDB server. You can do this by running the `mongod` command.

5. Create a `.env` file in the root directory and provide the following environment variables:

   ```
   PORT=<port-number>
   MONGODB_URI=<mongodb-connection-uri>
   ```

   Replace `<port-number>` with the desired port number for the server, and `<mongodb-connection-uri>` with the MongoDB connection URI.

6. Start the server:

   ```bash
   npm start
   ```

   The server will start running at the specified port.

## API Endpoints

- `GET /users`: Get all users.
- `GET /users/:id`: Get a single user by ID.
- `POST /users`: Create a new user.
- `PATCH /users/:id`: Update a user.
- `DELETE /users/:id`: Delete a user.
