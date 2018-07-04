# Images #

Create image
docker run hello-world
- run means create an instance of an image, which is then called a container
- hello-world represents the image from which the container is made

Display images
docker images
- see list of Docker images on the system
Example:
sudo docker images

Download images
docker run image
Example:
sudo docker run centos

Remove images
docker rmi ImageID
Example:
sudo docker rmi 12346789012

Return Image ID’s of images
docker images -q
Example;
sudo docker images -q

Inspect image or container
docker inspect RepositoryName
Example:
sudo docker inspect jenkins


# Containers #

Run container
sudo docker run -t centos /bin/bash

List containers (currently running)
docker ps
Example:
sudo docker ps

List containers (all)
docker ps -a
Example:
sudo docker ps -a

Docker history
docker history ImageID
- shows all the commands run against that image
Example:
sudo docker history centos


# Working With Containers #

