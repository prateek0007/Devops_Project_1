# DevOps Project 1 🚀

## Overview
This project demonstrates an end-to-end DevOps pipeline including CI/CD, containerization, Kubernetes deployment, and infrastructure automation.

## Tech Stack
- FastAPI
- Docker (upcoming)
- Kubernetes (upcoming)
- Terraform (upcoming)

## Status
Day 1: Project setup and FastAPI app created ✅


## Day 2: Dockerization ✅

- Created Dockerfile
- Built container image
- Ran app inside container
- Optimized using .dockerignore

## Day 3: Docker Hub + CI/CD Automation 🚀

### What I did
- Pushed Docker image to Docker Hub
- Created a CI/CD pipeline using GitHub Actions
- Automated Docker image build and push on every commit

### CI/CD Workflow
- Code pushed to GitHub
- GitHub Actions triggers pipeline
- Docker image is built automatically
- Image is pushed to Docker Hub

### Docker Hub Repository
🔗 https://hub.docker.com/r/prateekmall/devops-app

### Key Learning
- Importance of automation in DevOps
- Secure authentication using Docker access tokens
- How CI/CD pipelines eliminate manual work

### Status
CI/CD pipeline successfully building and pushing images ✅

## Day 4: Kubernetes Deployment ☸️

### What I did
- Deployed the application on Kubernetes
- Created a Deployment with 2 replicas
- Exposed the application using a NodePort Service
- Verified service and pod status using kubectl

### Kubernetes Resources
- **Deployment:** `devops-app`
- **Service:** `devops-service`
- **Replicas:** `2`
- **Service Type:** `NodePort`
- **Accessible at:** `http://localhost:30007`

### Commands Used
```bash
kubectl apply -f k8s/
kubectl get pods
kubectl get svc







