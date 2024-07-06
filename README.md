
# Expense Tracker

## Project Overview

Expense Tracker is a full-stack React application designed to help users manage their expenses. The application features a backend for handling API requests and database interactions, and a frontend for managing the user interface. The database used is MongoDB, hosted on MongoDB Atlas.

## Folder Structure

```
/expense-tracker
  ├── /backend
  └── /frontend
```

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed
- MongoDB Atlas account and cluster setup

## Backend Setup

1. Navigate to the backend directory:

   ```bash
   cd backend
   ```

2. Install the required packages:

   ```bash
   npm install
   ```

3. Create a `.env` file in the backend directory with the following environment variables:

   ```env
   MONGO_URI=your_mongodb_atlas_connection_string
   PORT=your_preferred_port_number
   ```

4. Start the backend server:

   ```bash
   npm start
   ```

   The backend server should now be running on the port specified in the `.env` file.

## Frontend Setup

1. Navigate to the frontend directory:

   ```bash
   cd ../frontend
   ```

2. Install the required packages:

   ```bash
   npm install
   ```

3. Start the frontend development server:

   ```bash
   npm start
   ```

   The frontend server should now be running and typically accessible at `http://localhost:3000`.

## Connecting Frontend to Backend

Ensure the frontend is set up to make requests to the backend server. You may need to configure the API endpoint URLs in the frontend code to match the backend server's URL and port.

## License

This project is licensed under the MIT License.
