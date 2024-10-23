# User Authentication and Profile Management API

This project is a simple API for user registration, authentication, and profile management, built using **FastAPI**. It supports secure authentication via JWT and allows users to manage their profiles after logging in.

## Features

- **User Registration**: Users can sign up with an email and password.
- **User Login**: Registered users can log in to get a JWT for authenticated requests.
- **Password Hashing**: Passwords are securely hashed using `bcrypt`.
- **Profile Management**:
  - **GET /profile**: Retrieve the user's profile information.
  - **PUT /profile**: Update the user's profile information (email and name).
- **JWT Authentication**: The API supports secure token-based authentication using JSON Web Tokens (JWT).
