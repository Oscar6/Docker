// Docker File Setup

ARG_CODE_VERSION=16.04

FROM ubuntu:${CODE_VERSION}

RUN apt-get update -y

CMD ["bash"]

// Run the following in command prompt
    docker build -t img_from .

// Search
    docker search (name of image):(veriosn)

// Show running containers
    docker container ls

// Show all containers
    docker container ls -a

// Remove container
    docker container rm (first 3 characters of container)

// Run Docker in background
    docker container run -d -p 8080:80 --name mynginx nginx

// Running Docker with MySQL
    docker container run -d -p 3306:3306 --name mysql --env MYSQL_ROOT_PASSWORD=123456 mysql

// Check properties
    docker info

// Check Gradle properties
    gradle properties

Continue Angular + Firebase course