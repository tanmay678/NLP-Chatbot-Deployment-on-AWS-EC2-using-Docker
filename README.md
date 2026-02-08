# Dockerized Application Deployment on AWS EC2

## Objective
To deploy a containerized Flask-based application using Docker and expose it
over HTTP, focusing on containerization and cloud deployment fundamentals.

---

## Tech Stack
- Python (Flask)
- Docker
- AWS EC2 (Ubuntu)
- GitHub

---

## Project Overview
This project demonstrates how a Flask application can be packaged into a
Docker container and deployed on a Linux server.

The focus of this project is on:
- Docker image creation
- Container execution
- Port mapping
- Debugging container networking issues

---

## Key Steps Performed

### 1. Docker Image Creation
- Created a Docker image using a Dockerfile
- Installed dependencies using `requirements.txt`
- Defined the application startup command

### 2. Container Execution
- Ran the container in detached mode
- Mapped host and container ports correctly
- Verified the application was running inside the container

### 3. Debugging & Troubleshooting
- Used `docker logs` to identify port mismatch issues
- Identified that the application was running on port 3000
- Corrected Docker port mapping to match the application port
- Verified application access using curl and browser

---

## Outcome
Successfully deployed and accessed the application via HTTP, gaining practical
experience with Docker containerization and Linux-based deployment workflows.

This project focuses on infrastructure and deployment rather than application
logic.

