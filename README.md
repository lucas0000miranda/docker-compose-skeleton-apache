# docker-compose-skeleton-apache
A very basic skeleton for up a APACHE env with MySQL and Debian.

## Setup

### Pre-requisites:

* Docker
* docker-compose

#### About Docker

Install Docker for your platform.

* Mac: https://store.docker.com/editions/community/docker-ce-desktop-mac
* Windows: https://store.docker.com/editions/community/docker-ce-desktop-windows
* Linux: Please see your distributions package management system

#### About docker-compose

Install docker-compose for your platform.

* Mac: Included with Docker
* Windows: Included with Docker
* Linux: Please see your distributions package management system

### Installation

First we need to clone the project.

```bash
cd ~/code # or whatever directory you keep your projects in

git clone git@github.com:lucas0000miranda/docker-compose-skeleton-apache.git
cd docker-compose-skeleton-apache
```

Next we up the project:

```bash
docker-compose up
```

You are ready to use it!

Check some useful commands:

```bash
* docker ps -> List your running containers

* docker images -a -> List all yours images

* docker exec -it container_id bash -> Let you inside the container as a O.S user

* docker rmi -f image_id -> delete the image

* docker inspect container_id -> Inspect the container (ipaddress, name etc)

* docker-machine create machine_name -> creates a docker VM

* docker-machine rm machine_name -> Removes the docker VM

* docker run -d --publish your_port:docker_port image_name -> make the image works in the same port of yours

* docker-compose run --rm composer install -> To run composer install in the container

```
