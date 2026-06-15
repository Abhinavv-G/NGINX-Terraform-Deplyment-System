# NGINX Load-Balanced CI/CD Platform

Containerized microservices platform where NGINX acts as a reverse proxy 
and Round Robin load balancer across multiple Flask backend instances, 
with automated builds via Jenkins CI/CD pipeline.

## Architecture
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/c10dba65-781c-45e1-bc42-fbf35784423f" />

## Tech Stack
- Jenkins | GitHub (CI/CD)
- Docker + Docker Compose (containerization)
- NGINX (reverse proxy, load balancing)
- Python Flask (backend services)

## Key Concepts Implemented
- Round Robin load balancing across N Flask containers
- Docker bridge networking with DNS-based service discovery
- NGINX upstream configuration for traffic distribution
- Jenkins pipeline: Clone → Build → Deploy
