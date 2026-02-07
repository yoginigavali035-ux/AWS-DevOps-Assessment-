## AWS & DevOps Internship Assignment — Simple README


📌## Project Overview

This project demonstrates deployment of a simple Frontend + Backend + Database application using Docker and AWS services including EC2, Application Load Balancer, and Auto Scaling Group. The goal is to build a working cloud‑ready architecture using cost‑optimized resources.

The application consists of:

Simple HTML frontend

Python Flask backend API

MySQL database

Docker containerization

AWS EC2 deployment

Load balancing and auto scaling
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Project Architecture

aws-devops-assignment/
├─ backend/
│ ├─ Dockerfile
│ ├─ index.js
│ ├─ package.json
│ └─ frontend/
│ ├─ index.html
│ ├─ register.html
│ └─ login.html
└─ docker-compose.yml
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Technology Stack

Frontend: HTML + JavaScript

Backend: js

Database: MySQL

Containerization: Docker + Docker Compose

Cloud: AWS EC2

Scaling: Auto Scaling Group

Load Balancing: Application Load Balancer

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Phase 1 — Application

Created Flask API (/users endpoint)

Connected Flask to MySQL

Created simple HTML frontend

Verified DB connection
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Phase 2 — Docker

Created Dockerfile

Created docker-compose.yml

Ran app + MongoDb in containers

Run:
docker compose up -d

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Phase 3 — EC2 Deployment

Launched t2.micro EC2

Installed Docker

Ran containers on EC2

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Phase 4 — Load Balancer & Scaling

Created Application Load Balancer

Created Target Group

Attached Auto Scaling Group

Scaling based on CPU usage

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Cost Optimization

Used free‑tier t2.micro

Minimal storage

Auto Scaling enabled

No over‑provisioning

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Troubleshooting

![alt image]("https://github.com/yoginigavali035-ux/AWS-DevOps-Assessment-/blob/master/screenshots/users.jpeg")

![alt image]("https://github.com/yoginigavali035-ux/AWS-DevOps-Assessment-/blob/master/screenshots/get%20error.jpeg")

![alt image]("https://github.com/yoginigavali035-ux/AWS-DevOps-Assessment-/blob/master/screenshots/front%20end.jpeg")

![alt image]("https://github.com/yoginigavali035-ux/AWS-DevOps-Assessment-/blob/master/screenshots/form.jpeg")

![alt image]("https://github.com/yoginigavali035-ux/AWS-DevOps-Assessment-/blob/master/screenshots/directory%20error.jpeg")

![alt image]("https://github.com/yoginigavali035-ux/AWS-DevOps-Assessment-/blob/master/screenshots/code.jpeg")

![alt image]("https://github.com/yoginigavali035-ux/AWS-DevOps-Assessment-/blob/master/screenshots/code.jpeg")

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## conclusion

This project successfully demonstrates a simple full-stack application using Flask and MySQL, containerized with Docker and deployed on AWS EC2.
The setup includes secure access, load balancing, and auto scaling for reliability and cost optimization. 
It shows practical understanding of DevOps workflow from application build to scalable cloud deployment.














