# Docker Demo

This is a demo to explain Docker and Docker Compose.

## Build a Docker Image
```
docker build -t demo:v1 .
```

## Run a Docker Image (as a Container)
```
docker run demo:v1
```

with port mapping:
```
docker run -p 8080:80 demo:v1
```

## Build using Docker Compose

```
docker-compose up
```

Full video can be found here:
https://youtu.be/slcKUz6CyLg
