# TaskWise

TaskWise is a MERN Stack project comprising a frontend and backend. This project is structured with the frontend and backend in separate directories.

## Project Structure

- `frontend/`: Contains the React application.
- `backend/`: Contains the Express and MongoDB backend.

## Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or later)
- [MongoDB](https://www.mongodb.com/try/download/community) (Make sure MongoDB is running on your local machine or set up a remote database)

## Getting Started

### Backend

1. Navigate to the `backend/` directory:

    ```bash
    cd backend
    ```

2. Install the backend dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the `backend/` directory and add your environment variables. For example:

    ```env
    MONGO_URI=mongodb://localhost:27017/taskwise
    PORT=5000
    ```

4. Start the backend server:

    ```bash
    npm start
    ```

    The backend server will start on `http://localhost:5000`.

### Frontend

1. Navigate to the `frontend/` directory:

    ```bash
    cd ../frontend
    ```

2. Install the frontend dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the `frontend/` directory and add your environment variables. For example:

    ```env
    REACT_APP_API_URL=http://localhost:5000
    ```

4. Start the frontend development server:

    ```bash
    npm start
    ```

    The frontend application will be available at `http://localhost:3000`.

## Usage

1. Make sure both the backend and frontend servers are running.
2. Open `http://localhost:3000` in your web browser to access the application.

## Scripts

- **Backend**
  - `npm start`: Start the backend server.
  - `npm test`: Run backend tests (if any).

- **Frontend**
  - `npm start`: Start the frontend development server.
  - `npm test`: Run frontend tests (if any).

## Contributing

If you'd like to contribute to TaskWise, please fork the repository and submit a pull request. Be sure to follow the project's coding standards and include tests for new features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please contact [Shwetas Dhake](mailto:your-email@example.com).

