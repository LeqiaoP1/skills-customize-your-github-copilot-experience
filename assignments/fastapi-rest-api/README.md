# 📘 Assignment: FastAPI REST API

## 🎯 Objective

Build a REST API using the FastAPI framework to learn endpoint design, request validation, and API testing with modern Python tools.

## 📝 Tasks

### 🛠️ Define API Models and Routes

#### Description
Create FastAPI data models using Pydantic and define endpoints for listing, creating, and retrieving items.

#### Requirements
Completed program should:

- Use FastAPI to create an application instance.
- Define Pydantic models for request and response data.
- Implement at least two routes: one to return a list of items and one to add a new item.
- Validate request payloads automatically with the Pydantic model.

### 🛠️ Implement CRUD Endpoint Behavior

#### Description
Add endpoints that support common REST operations and handle errors cleanly.

#### Requirements
Completed program should:

- Support `GET` to fetch all items and `GET` to fetch a single item by ID.
- Support `POST` to create a new item with JSON request data.
- Return appropriate HTTP status codes for success and not-found cases.
- Provide a JSON error response when a requested item does not exist.

### 🛠️ Run and Test the API

#### Description
Run the FastAPI server locally and confirm the API works using Swagger UI or simple HTTP requests.

#### Requirements
Completed program should:

- Start the FastAPI server successfully with Uvicorn.
- Expose the OpenAPI docs at `/docs` or `/redoc`.
- Demonstrate API usage by successfully sending requests to the implemented endpoints.
- Include example request/response behavior in the assignment instructions if helpful.
