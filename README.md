# Mini PaaS Project

A simple Flask app containerized with Docker.

## Features
- Flask web app
- Health check endpoint
- Dockerized application

## Run locally

```bash
docker build -t mini-paas:v1 .
docker run -d -p 5000:5000 --name mini-paas-container mini-paas:v1
