# Day 2 – NGINX using Docker

## Objective
Deploy a custom web page using NGINX inside a Docker container.

## Steps Performed

1. Created a custom HTML file
2. Created a Dockerfile using nginx base image
3. Built a custom Docker image
4. Ran the container with port mapping
5. Accessed the web page from browser

## Docker Commands Used

```bash
docker build -t sweda-nginx .
docker run -d -p 8084:80 --name sweda-nginx-container sweda-nginx
docker ps

