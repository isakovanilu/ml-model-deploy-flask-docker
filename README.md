
# Python FastAPI Application
This repository contains a Python application built with FastAPI and containerized using Docker. The application can be deployed using the provided Dockerfile and exposes an API endpoint.
## Project Structure
Project Structure
/app: Directory containing the FastAPI application code.
requirements.txt: Python dependencies required for the application.
Prerequisites
To run this project, ensure you have the following installed on your machine:

Docker
Python 3.11
Installation
1. Clone the repository:
```
git clone url
```
2. Build the Docker image:
```
docker build -t my-fastapi-app .
```
3. Run the Docker container:
```
docker run -p 8000:8000 my-fastapi-app
```
This will start the FastAPI application and make it accessible on http://localhost:8000.


