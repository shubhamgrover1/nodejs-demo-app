# Node.js Demo App + CI/CD with GitHub Actions

This is a beginner-friendly Node.js app that is automatically built and deployed using GitHub Actions and Docker.

## 📦 Tech Stack

- Node.js
- Docker
- GitHub Actions (CI/CD)

## 🚀 CI/CD Pipeline

On every push to the `main` branch:
- The code is tested (basic placeholder test)
- A Docker image is built
- The image is pushed to Docker Hub

## 🧪 Run Locally

```bash
docker pull <your-dockerhub-username>/nodejs-demo-app:latest
docker run -p 3000:3000 <your-dockerhub-username>/nodejs-demo-app
