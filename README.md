# Dockerized Nginx Web Server on AWS EC2

## Project Overview
This project demonstrates how to deploy a containerized Nginx web server using Docker on an AWS EC2 Ubuntu instance.

## Tools Used
- AWS EC2
- Ubuntu Linux
- Docker
- Docker Compose
- Nginx
- Git & GitHub

## Steps Performed
1. Installed Docker on EC2
2. Created custom HTML page
3. Built Docker image using Dockerfile
4. Deployed container using Docker Compose
5. Exposed port 80 for web access

## Run Project
```bash
docker compose up -d --build
docker ps
