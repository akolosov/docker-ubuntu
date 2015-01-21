## Ubuntu Dockerfile


This repository contains **Dockerfile** of [Ubuntu](http://www.ubuntu.com/) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/akolosov/ubuntu/) published to the public [Docker Hub Registry](https://registry.hub.docker.com/).


### Base Docker Image

* [ubuntu:14.04](https://registry.hub.docker.com/u/library/ubuntu/)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://registry.hub.docker.com/u/akolosov/ubuntu/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull akolosov/ubuntu`

   (alternatively, you can build an image from Dockerfile: `docker build -t="akolosov/ubuntu" github.com/akolosov/docker-ubuntu`)


### Usage

    docker run -it --rm akolosov/ubuntu
