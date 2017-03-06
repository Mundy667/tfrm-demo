# tfrm-demo
Demo for Technologie Forum Rhein-Main 2017

## Instructions

First, build the current codebase:
```
docker build . -t "webapp_build"
```

Let's make sure it was built successfully:
```
docker images
```

Let's show our current Docker Volumes:
```
docker volume ls
```

Bring up the application stack:
```
docker-compose up
```

