# 📘 Assignment: REST APIs with FastAPI

## 🎯 Objective

Learn how to build RESTful APIs using the FastAPI framework. This assignment will guide you through creating endpoints, handling requests, and returning JSON responses.

## 📝 Tasks

### 🛠️ Create a Basic API

#### Description
Set up a FastAPI project and create a basic API with at least two endpoints:

1. A `GET /` endpoint that returns a welcome message.
2. A `POST /items/` endpoint that accepts JSON data and returns the created item.

#### Requirements
Completed program should:

- Use FastAPI to define the API.
- Include a `GET /` endpoint that returns a JSON response like `{ "message": "Welcome to FastAPI!" }`.
- Include a `POST /items/` endpoint that accepts a JSON payload with `name` and `price` fields and returns the same data with an added `id` field.
- Validate the input data using Pydantic models.

### 🛠️ Add Error Handling

#### Description
Enhance the API to handle errors gracefully.

#### Requirements
Completed program should:

- Return a `400 Bad Request` error if the input data for `POST /items/` is invalid.
- Return a `404 Not Found` error for undefined routes.

### 🛠️ Documentation

#### Description
Leverage FastAPI's built-in documentation.

#### Requirements
Completed program should:

- Automatically generate OpenAPI documentation accessible at `/docs`.
- Include clear descriptions for each endpoint and its parameters.

---

&copy; 2025 Mergington High School