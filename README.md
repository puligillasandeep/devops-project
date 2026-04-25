# DevOps Project

This project demonstrates deploying a containerized web application using Docker on AWS EC2.

## Tech Stack
- Docker
- Nginx
- AWS EC2
- GitHub

## What I Did
- Created a simple HTML webpage
- Wrote a Dockerfile to build a custom nginx image
- Ran the container using Docker
- Deployed the container on AWS EC2
- Exposed it using port mapping
- Pushed project code to GitHub

## How It Works
1. HTML file is created
2. Dockerfile copies HTML into nginx image
3. Docker builds the image
4. Container is created from image
5. Nginx inside container serves the webpage
6. Browser accesses it via public IP

## Commands Used

Build image:
docker build -t myapp .

Run container:
docker run -d -p 80:80 myapp

## Output
A live webpage served using nginx on an AWS EC2 instance.

## Learning Outcome
- Understood Docker image vs container
- Learned port mapping and volume concepts
- Deployed application on cloud (AWS EC2)
- Connected local development with cloud deployment
