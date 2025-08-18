
# CI/CD Demo App

This is a simple Node.js app to demonstrate a CI/CD pipeline using GitHub Actions and Docker.

## Prerequisites
- Docker
- Docker Hub account and Personal Access Token
- GitHub account

## How to run locally
- Build and run Docker image:
  ```
  docker build -t yourdockerhubusername/ci-cd-demo .
  docker run -p 8080:3000 yourdockerhubusername/ci-cd-demo
  ```
- Or use Docker Compose:
  ```
  docker compose up
  ```

## CI/CD Workflow

The GitHub Actions workflow:
- Runs tests
- Builds the Docker image
- Pushes to Docker Hub

## Links
- GitHub Actions badge (add your own)
- Docker Hub image link

## Screenshots
- Add screenshots of the deployed app and workflow results here.
