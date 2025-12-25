# Docker Compose Frontend–Backend Project

## Description
This project demonstrates a simple multi-container application using Docker Compose.

It includes:
- A backend container (Flask) that returns a message
- A frontend container (Nginx) that displays the message
- Both containers run and communicate using Docker Compose

## Technologies Used
- Docker
- Docker Compose
- Nginx
- Python (Flask)
- Linux

## Project Structure
backend/ → Backend application and Dockerfile
frontend/ → Frontend HTML and Dockerfile
docker-compose.yml → Runs both containers together



## How to Run
```bash
docker compose up -d --build
Frontend:
http://localhost:8081
Backend:
http://localhost:5000

Key Learning
Multi-container setup using Docker Compose
Port mapping and container isolation
Frontend and backend separation


Save:
- **CTRL + O → Enter**
- **CTRL + X**

---

## ⬆️ Commit and push README

```bash
git add README.md
git commit -m "Add README"
git push
