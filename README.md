# Docker_Web
testing out docker !
# NGINX Docker Web Server

This is a simple Dockerized web server using **NGINX**. It serves a custom `index.html` page and uses a custom `nginx.conf` configuration file (optional).

---

## installation
# first build the docker image 
docker build -t bridge .

## run container
docker run -d -p 80:80 bridge

## open browser and visit
http://localhost:80

## 🛠 Requirements

Before you can build and run this project, ensure you have the following installed on your system:
