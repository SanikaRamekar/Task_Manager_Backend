Task Manager Backend API
A RESTful backend service for the Task Manager Mobile Application.

Features
User authentication using JWT
Secure password hashing
Token-based API authorization
Task CRUD operations
MongoDB database integration
Structured error handling

Tech Stack
Node.js
Express.js
MongoDB Atlas
JWT Authentication
bcrypt
Postman (API testing)

Setup Instructions

Backend
Clone the backend repository
Run npm install
Create a .env file with required credentials
Start the server using node server.js

Environment Variables
PORT=5000
MONGO_URI=MongoDB connection string
JWT_SECRET=JWT secret key

API Endpoints

Authentication
POST /api/auth/login
POST /api/auth/register

Tasks (Protected)
GET /api/tasks
POST /api/tasks
PUT /api/tasks/:id
DELETE /api/tasks/:id

Authorization Header
Authorization: Bearer <JWT_TOKEN>

Testing
API tested using Postman
Handles invalid input and authentication errors

Status
Backend completed and integrated with Android application

- Sanika Ramekar
