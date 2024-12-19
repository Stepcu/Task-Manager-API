# Task Manager App

The **Task Manager App** is a full-stack application designed to help users organize and manage their tasks effectively. This app features a user-friendly interface, a powerful RESTful API backend, and seamless integration between the frontend and backend.

## Features

- **Task Operations**: Create, update, mark as complete, and delete tasks.
- **User Authentication**: Secure login and registration system.
- **Real-Time Updates**: Synchronization between the frontend and backend.
- **Responsive Design**: Fully optimized for desktop and mobile use.
- **Scalable Backend**: Built with Node.js, Express, and MongoDB.

## Tech Stack

### Frontend
- React.js
- HTML/CSS
- Axios (for API integration)

### Backend
- Node.js
- Express.js
- MongoDB
- JWT (JSON Web Tokens) for authentication
- dotenv (for environment variables)

## Installation

### Prerequisites
- Node.js and npm installed
- MongoDB installed and running locally or using a cloud-based MongoDB service

### Backend Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/task-manager-api.git
   cd task-manager-api
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the root of the project and add the following variables:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```
4. Start the backend server:
   ```bash
   npm start
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd task-manager-frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the frontend development server:
   ```bash
   npm start
   ```

## Usage

1. Open your browser and navigate to the frontend (e.g., `http://localhost:3000`).
2. Register a new user account or log in with an existing account.
3. Start managing your tasks!

## API Endpoints

### Authentication
- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Login a user

### Tasks
- `GET /api/tasks` - Get all tasks
- `POST /api/tasks` - Create a new task
- `PUT /api/tasks/:id` - Update a task
- `DELETE /api/tasks/:id` - Delete a task

