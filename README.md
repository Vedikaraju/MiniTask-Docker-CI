MiniTask API — Docker & CI/CD

Project Overview

This project demonstrates containerization and CI/CD automation using a FastAPI-based MiniTask API.

Technologies Used

- Python
- FastAPI
- Docker
- Docker Compose
- GitHub Actions
- Pytest

Features

- REST API for task management
- Automated API testing using Pytest
- Docker containerization
- Docker Compose configuration
- Automated CI pipeline using GitHub Actions

Project Structure

- "app/" – Application source code
- "tests/" – Automated test cases
- ".github/workflows/" – GitHub Actions workflow
- "Dockerfile" – Docker image configuration
- "compose.yaml" – Docker Compose configuration
- "requirements.txt" – Project dependencies

Run Locally

pip install -r requirements.txt
uvicorn app.main:app --reload

Open "http://localhost:8000/docs" to access the API documentation.

Run with Docker

docker compose up --build

Run Tests

pytest

Author

Vedika Raju
