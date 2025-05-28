# JWT Authentication API in ASP.NET Core

This project is a simple **JWT-based authentication API** built with **ASP.NET Core**. It allows users to register and log in securely, returning a **JSON Web Token (JWT)** that can be used to authenticate further API requests.

## Features

- User **registration** and **login**
- JWT-based **authentication**
- Minimal API setup with ASP.NET Core
- Swagger UI for testing endpoints
- Clear structure and easy to extend

## Technologies Used

- ASP.NET Core 6 / 7
- JSON Web Tokens (JWT)
- C#
- Swagger / Swashbuckle for API documentation

## How JWT Authentication Works

1. A user **registers** with a username and password.
2. The user then **logs in**, and the server returns a **JWT token**.
3. The client can include this token in the `Authorization` header for future requests to access protected endpoints.

