# Day 3 - Alpine NGINX Web Page

This project demonstrates creating a custom web page using:

- Alpine Linux (lightweight base image)
- NGINX web server
- Docker containerization

## Build Image
docker build -t day3-alpine-nginx .

## Run Container
docker run -d -p 8086:80 --name day3-alpine-nginx day3-alpine-nginx

## Access Application
http://<VM-IP>:8086

## Outcome
Successfully served a custom HTML page using Alpine + NGINX.
# Day 3 - Alpine NGINX Web Page

This project demonstrates creating a custom web page using:

- Alpine Linux (lightweight base image)
- NGINX web server
- Docker containerization

## Build Image
docker build -t day3-alpine-nginx .

## Run Container
docker run -d -p 8086:80 --name day3-alpine-nginx day3-alpine-nginx

## Access Application
http://<VM-IP>:8086

## Outcome
Successfully served a custom HTML page using Alpine + NGINX.
