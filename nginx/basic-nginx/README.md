# Docker Guide

https://docs.docker.com/get-started/02_our_app/

# Build docker image & run

```
docker build -t basic-nginx .
docker run -dp 80:80 basic-nginx
```
alternatively
```
docker-compose up --build
```


