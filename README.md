# docker-ubuntu-docker
Installed docker, docker-compose and more


# Usage

```Dockerfile
FROM ushios/ubuntu-docker:latest

RUN docker-compose build && \
    docker-compose up -d

```
