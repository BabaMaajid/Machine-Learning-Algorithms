# Docker Installation

https://docs.docker.com/desktop/

# Commands on Hands On

### docker --version
docker run hello-world
### docker pull busybox
- The docker pull busybox command is used to download the latest version of the BusyBox image from Docker Hub. BusyBox is a lightweight and     versatile Unix toolset often used in container environments.
### docker images
 - The docker images command is used to list the Docker images that are currently available on your system. If you have successfully pulled the BusyBox image or any other images, you should be able to see them in the output of this command.
### docker run busybox
- Running docker run busybox will start a container based on the BusyBox image. Since the BusyBox image is minimal and contains a small set of essential Unix utilities, this command will start a lightweight container that executes a shell inside it.
docker run busybox echo "Hello, Docker!"
### docker ps
The docker ps command is used to list the currently running Docker containers. If you've just run a container using the docker run busybox command, you might not see it in the output of docker ps because it likely exited immediately after running the default command.
### docker ps -a
- To see all containers, including those that have exited, you can use the -a option:
### docker run -it busybox sh
-The docker run -it busybox sh command runs a Docker container interactively based on the BusyBox image and starts a shell (sh) within the container. Let's break down the command:
### docker rm <container_id>
- The docker rm command is used to remove one or more containers. You would replace <container_id> with the actual ID or name of the container you want to remove.


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

