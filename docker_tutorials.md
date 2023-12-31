# What is Docker
- Docker is a containerization platform which packages application and all its dependencies together in the form of Contianers, to ensure that application works seamlessly in any environmment be it Devleopment/Test/Production.
# Benifits 
- RAM consusmed by applications by packaging them into containers.
- Containers are light-weight can be easily shared via Docker Hub(Registry Provided by the docker).
# What is Containeriazation Technology
- Containeriazation technolgy refers to practice of encapsualting an application and its dependencies into a self-contained unit called a container.
- Containerization technology enables the bundling of an application with its dependicies,libraries,and runtime environment,ensuring that it can be executed reliably on any system that supports containers,regardless of the underlying infrastructure operating system.
- Containers leverage operating system level virtualization, where multiple containersshare the same host operating system kernel but are isolated from one another.
# Benifits of Containerization
 - **Portabillity**: Containers are  portable across different systems and platforms
 - **Scalabilty** : Contianrs can be easily scaled horizontally by running multiple instances of the same container across a cluster of machines.
 - **Efficiency**: Conatiners are lightweight and have minimal overhead compared to traditional VMs. they share the same host OS, which reduces resource consumption an allows for faster startup times.
 - **Consistency**: Contianers ensure consistent behaviour across different environments. Since the entire runtime environment is bundled within the container, there are fewer dependencies or conflicts with the underlying OS, leading more predictable behavaiour.
- **DevOps Enablement**: Continerization facilitates the adoptation of DevOps practices by providing a standardized and reproducible deployment unit.
# Docker Architecture
-  Docker engine: At the core of Docker Architetture is the docker Engine. It is reponsible for building, and managinh containers.
-  Docker Image : Docker Images are the building blocks of containers. An image is readonly templat that contains the necessry files, libraries and dependencies required to run application.
-  Docker containers: Containers are the running instances of docker Images.
-  Docker Registry: A docker registry is a central repository for storing and distributing Docker Iamges.  Docker hub is the default public resgistryt provided by docker,hosting a vast collection of official and community build images.
-  Additional Components: Docker Volume, Docker Networks, and Docker Compose.
# Host OS with Docker Engine
- The host os is the underlying OS on which docker runs.
- **Docker Engine**: also know as Docker daemon, is the core component of Docker that interacts with the host OS to manage containers.
- **Docker Engine** : is reponsible for container runtime and provides tools for building, running, and managing containers.
# Docker CLI
- The docker Command-line Interface(CLI) is a powerful tool for interacting with Docker Engine and Managing containers.
- Docker CLI provides a wide range of commands to build, run, mange and troublehoot containers effectively.
