# 📘 Assignment: FastAPI REST APIs

## 🎯 Objective

Build a RESTful API using FastAPI and Pydantic to practice endpoint design, request validation, and API documentation.

## 📝 Tasks

### 🛠️ Create the FastAPI Application

#### Description
Set up a FastAPI app with a basic project structure and a root endpoint.

#### Requirements
Completed program should:

- Create a FastAPI app instance in `starter-code.py`.
- Define a root endpoint (`/`) that returns a welcome message.
- Run the app using `uvicorn` or a similar ASGI server.

### 🛠️ Define Pydantic Models and Validation

#### Description
Create request and response models using Pydantic to validate API input and structure output.

#### Requirements
Completed program should:

- Define a Pydantic model for an item resource.
- Use the model to validate incoming request data.
- Return item data in the response using a Pydantic model.

### 🛠️ Implement CRUD Endpoints

#### Description
Add endpoints for creating, reading, updating, and deleting items.

#### Requirements
Completed program should:

- Create an endpoint to add a new item with POST.
- Create an endpoint to retrieve an item by ID with GET.
- Create an endpoint to update an item with PUT or PATCH.
- Create an endpoint to delete an item with DELETE.
- Store items in a simple in-memory structure for testing.
- Use clear API responses for success and failure cases.
