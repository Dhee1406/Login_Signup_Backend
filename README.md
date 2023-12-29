# Node.js Authentication API

This Node.js project provides authentication APIs using Express and MongoDB. It includes signup, login, user details, and more. Additionally, the project implements protected routes using an authentication middleware and uses JWT tokens for authentication.

## Getting Started

### Prerequisites

Make sure you have Node.js and npm installed on your machine.

### Install dependencies
npm install

#### Create a .env file in the root directory and add the following environment variables
MONGO_URL=your_mongo_db_url
JWT_SECRET_KEY=your_jwt_secret_key
JWT_REFRESH_SECRET_KEY=your_jwt_refresh_secret_key
JWT_ADMIN_SECRET_KEY=your_jwt_admin_secret_key
DB_NAME=your_database_name
COMPANY_EMAIL=your_company_email

##### Run the application using nodemon
nodemon

The server will start at http://localhost:8000 by default.

API Endpoints
Signup: /auth/register (POST)

Create a new user account.
Login: /auth/login (POST)
