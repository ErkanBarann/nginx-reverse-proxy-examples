# 🌐 NGINX Reverse Proxy Examples (Flask API + Static Frontend)

This project demonstrates how to set up **NGINX as a reverse proxy** for:
- Serving static frontend content
- Forwarding API requests to a Flask backend

## 📦 Services

- **nginx**: Handles all incoming traffic and routes `/api` requests to the backend and all other traffic to the static frontend.
- **backend**: A simple Flask application that serves an API endpoint.
- **frontend**: A static HTML page served by NGINX.

## 🚀 Getting Started

### 1. Clone the repository and navigate to the project directory

```bash
git clone <repo-url>
cd nginx-reverse-proxy-examples
```

### 2. Run the stack with Docker Compose

```bash
docker compose up --build
```

### 3. Access the application

- Frontend: [http://localhost:8080](http://localhost:8080)
- API Endpoint: [http://localhost:8080/api](http://localhost:8080/api)

## 🧰 Requirements

- Docker
- Docker Compose

This example is ideal for understanding basic reverse proxying with NGINX in a Dockerized microservices architecture.