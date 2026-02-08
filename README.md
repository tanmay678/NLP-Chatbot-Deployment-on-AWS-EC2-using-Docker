# Dockerized Flask Application Deployment

## Objective
To deploy a containerized Flask-based application using Docker and expose it
over HTTP, focusing on Linux-based deployment, container networking, and
troubleshooting common runtime issues.

This project emphasizes infrastructure and deployment concepts rather than
application logic.

---

## Tech Stack
- Python (Flask)
- Docker
- Linux (Ubuntu)
- AWS EC2
- GitHub

---

## Project Overview
This project demonstrates how a Flask application can be packaged into a
Docker container and deployed on a Linux system and AWS EC2.

The primary focus areas include:
- Docker image creation using a Dockerfile
- Running containers with correct port mapping
- Debugging container networking issues using logs
- Verifying application accessibility over HTTP

---

## Key Implementation Steps

### 1. Docker Image Creation
- Created a Docker image using a Dockerfile
- Installed application dependencies using `requirements.txt`
- Defined application startup commands

### 2. Container Execution
- Ran the container in detached mode
- Configured host-to-container port mapping
- Verified container runtime status

### 3. Debugging & Troubleshooting
- Used `docker logs` to analyze application runtime behavior
- Identified a port mismatch between the application and Docker configuration
- Corrected port mapping to align with the application’s listening port
- Verified successful access using curl and browser

---

## Outcome
Successfully deployed and accessed the application via HTTP, gaining hands-on
experience in Docker containerization, Linux troubleshooting, and deployment
workflows relevant to entry-level cloud and infrastructure roles.

---

## Notes
This project focuses on deployment and troubleshooting skills and is not
intended to demonstrate advanced application development or machine learning
concepts.
