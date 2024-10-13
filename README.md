# Code Judging Platform

A robust, scalable code judging platform inspired by LeetCode. This platform enables users to write, test, and submit code against problem sets in a real-time, microservice-based environment. It supports high concurrency and is built to handle multiple users simultaneously through Docker containers and a microservices architecture.

## Table of Contents

- [Code Judging Platform](#code-judging-platform)
  - [Features](#features)
  - [Tech Stack](#tech-stack)
    - [Key Components](#key-components)

## Features

- **Real-Time Code Execution**: Compile and execute code in a secure sandbox environment.
- **Microservices Architecture**: Decoupled services for maximum scalability and fault tolerance.
- **Docker Containerization**: Each code submission runs in an isolated Docker container.
- **User Authentication and Profiles**: Secure login and profile management.
- **Admin Panel**: Manage problems, view user activity, and more.

## Tech Stack

- **Frontend**: ReactJS
- **Backend**: Node.js, Express.js, Dockerode
- **Database**: MySQL
- **APIs and Gateway**: REST API, gRPC, Kong Gateway
- **Containerization**: Docker, Docker Compose

### Key Components
![image](https://github.com/user-attachments/assets/9b2acfad-3080-4dc9-9afa-84632f75cd50)


1. **User Service**: Manages user data, authentication, and authorization.
2. **Problem Service**: Manages problem sets, including CRUD operations for admins.
3. **Execution Service**: Runs code in isolated Docker containers to ensure a secure execution environment.
4. **API Gateway**: Kong Gateway handles API requests and authentication across all services.

#### How Execution Service Works?
![image](https://github.com/user-attachments/assets/b324c379-ef1f-4f5c-baa6-79dd5120b0ec)



