# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to create a simple REST API with FastAPI by defining routes, handling JSON data, and validating request models.

## 📝 Tasks

### 🛠️ Create a FastAPI Application

#### Description
Set up a basic FastAPI app with a root endpoint and a simple item route.

#### Requirements
Completed program should:

- Import `FastAPI` and create an app instance.
- Add a `GET /` route that returns a welcome message.
- Add a `GET /items/{item_id}` route that returns the requested item ID.
- Run the app locally with `uvicorn` for testing.

### 🛠️ Build a Small REST API

#### Description
Expand the app to support creating and listing items using JSON request and response models.

#### Requirements
Completed program should:

- Define a Pydantic model for an item with a name and description.
- Add a `POST /items` endpoint to create a new item.
- Add a `GET /items` endpoint to return the current list of items.
- Return clear JSON responses for successful requests.
