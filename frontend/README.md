# React + Vite Chat App

This project is a full-stack real-time chat application built with React, Vite, Socket.io, TailwindCSS, and Daisy UI.

## Features:
- Real-time messaging with Socket.io
- User authentication and authorization with JWT
- Online user status
- Global state management with Zustand
- Error handling on both server and client

## Setup:

1.  **Install Dependencies:**
    ```bash
    cd frontend
    npm install
    ```
2.  **Environment Variables:**
    Create a `.env` file in the `frontend` directory (if it doesn't exist) and add the following:
    ```
    VITE_API_URL=http://localhost:5001/api
    ```
    *(Note: The backend API URL might need to be adjusted based on your backend setup.)*

## Running the App:

1.  **Start the backend server:**
    Navigate to the `backend` directory and run:
    ```bash
    cd ../backend
    npm install
    npm run dev
    ```
    *(Ensure your MongoDB is running and the `MONGODB_URI` is set in the backend's `.env` file.)*

2.  **Start the frontend development server:**
    Navigate back to the `frontend` directory and run:
    ```bash
    cd ../frontend
    npm run dev
    ```

