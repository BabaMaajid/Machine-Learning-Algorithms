# Docker Installation

https://docs.docker.com/desktop/

# Commands on Hands On

```
docker --version
docker run hello-world
### docker pull busybox
- The docker pull busybox command is used to download the latest version of the BusyBox image from Docker Hub. BusyBox is a lightweight and     versatile Unix toolset often used in container environments.
docker images
docker run busybox
docker run busybox echo "hello from busybox mlops"
docker ps
docker ps -a
docker run -it busybox sh
docker rm <container_id>
```

# 2. Hands On


```
docker run -d -P --name catgif manifoldailearning/catgif
docker ps
docker port catgif
docker stop catgif
docker run -p 8888:5000 manifoldailearning/catgif
docker build -t catgifv2 .
docker run -p 8888:5000 catgifv2
docker login
docker build -t yourusername/catgif .
docker push yourusername/catgif
```

