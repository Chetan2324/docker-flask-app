# Docker Flask App

## Description
This project demonstrates how to containerize a simple Flask web application using Docker.

## Features
- Simple Flask web app
- Dockerized using Dockerfile
- Runs on localhost:5000

## How to Run

1. Build the Docker image:
   docker build -t my-app .

2. Run the container:
   docker run -d -p 5000:5000 my-app

3. Open in browser:
   http://localhost:5000

## Screenshots
- Docker image build
- Running container
- docker ps output
