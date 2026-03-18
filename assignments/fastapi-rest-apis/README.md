# 📘 Assignment: REST APIs with FastAPI

## 🎯 Objective

Build a REST API using FastAPI to practice request handling, response modeling, and basic endpoint design in Python.

## 📝 Tasks

### 🛠️ Create a FastAPI Application

#### Description
Set up a FastAPI app and implement core endpoints for a simple resource such as books, tasks, or students.

#### Requirements
Completed program should:

- Create a FastAPI application instance.
- Include at least one `GET` endpoint that returns a list of items.
- Include at least one `POST` endpoint that accepts JSON input and adds a new item.
- Return responses in JSON format.

### 🛠️ Add Input Validation and Error Handling

#### Description
Use Pydantic models to validate request data and return clear errors for invalid operations.

#### Requirements
Completed program should:

- Define at least one Pydantic model for request or response data.
- Reject invalid input with appropriate HTTP status codes.
- Handle a missing resource case using a clear error response (for example, `404 Not Found`).
- Keep endpoint behavior consistent and easy to test with tools like Swagger UI.
