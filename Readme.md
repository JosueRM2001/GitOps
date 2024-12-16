# GitOps

This project demonstrates a GitOps workflow using Docker and GitHub Actions to automate the creation of a web application.

## Description

The application is designed to demonstrate the principles of GitOps, where changes pushed to the `main` branch trigger an automated process that rebuilds and updates the Docker image on Docker Hub.

## Technologies used

- Docker Desktop
- Visual Studio Code
- GitHub Actions
- Docker Hub

## Prerequisites
**To replicate or use this project, you need:**
- Install Visual Studio Code
```bash
https://code.visualstudio.com/
```
- Docker installed on your local machine at the following link:
```bash
https://www.docker.com/products/docker-desktop
```
- A Docker Hub account to store your images.
At the following link:
```bash
https://hub.docker.com/explore
```
- Git installed to manage the repository.
At the following link:
```bash
https://git-scm.com/
```

## Instructions to run the project locally

1. **Clone the repository**:

Clone the GitHub repository to your local machine:
```bash
https://github.com/JosueRM2001/GitOps.git
```
2. **Get the latest Docker image:**:

Get the latest image from Docker Hub:
```bash
docker pull erickjrm/programops:latest
```
3. **Get the latest Docker image:**:

Start the application in a Docker container:
```bash
docker run -d -p 8080:80 --name gitops erickjrm/programops:latest
```

4. **Access the application:**:

Open the web browser or Use tools like Postman to navigate to:
```bash
http://localhost:8080
```
![Captura de pantalla 2024-12-15 223142](https://github.com/user-attachments/assets/a9a8f391-2bea-4ded-85ac-2236242ba372)

