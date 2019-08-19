// Docker File Setup

ARG_CODE_VERSION=16.04

FROM ubuntu:${CODE_VERSION}

RUN apt-get update -y

CMD ["bash"]

// Run the following in command prompt
    docker build -t img_from .

// Search
    docker search (name of image):(veriosn)