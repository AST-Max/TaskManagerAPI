# Task Management API

A lightweight, high-performance RESTful API built rapidly using **C# and ASP.NET Core Minimal APIs**. 

## Features
- **CRUD Operations:** Complete Create, Read, and Delete functionality.
- **RESTful Standards:** Proper implementation of HTTP methods and status codes (`200 OK`, `201 Created`, `204 No Content`, `400 Bad Request`, `404 Not Found`).
- **Data Validation:** Prevents empty or invalid task entries at the API level.
- **In-Memory Storage:** Fast, lightweight state management for rapid prototyping and demonstration.

## API Endpoints
| Method | Endpoint | Description |
| :--- | :--- | :--- |
| `GET` | `/tasks` | Retrieve all tasks |
| `GET` | `/tasks/{id}` | Retrieve a specific task by ID |
| `POST` | `/tasks` | Create a new task (requires JSON body) |
| `DELETE` | `/tasks/{id}`| Delete an existing task by ID |

## Tech Stack
- C# 12
- .NET 8 (Minimal APIs)
