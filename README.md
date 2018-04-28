# Betty Docker Pep8 Image

## Docker Hackathon at Holberton School
This project was created for Holberton School's 2018 24 hour Docker Hackathon. Our task was simply to use Docker to make something.

## Requirements

Install Docker on Ubuntu 14.04 LTE:

```sh
sudo apt-get update
sudo apt-get install docker-ce
```

Install Docker on Windows or Mac OS:

- Go to [Docker](https://www.docker.com/get-docker)
- Download the Docker Community Edition (CE)

## Goal
This part of the project was to create a lightweight version of the pep8 1.7.0 docker container. This was made to run alongside the other 2 containers (Betty and Shellcheck) orchestrated with Docker Compose in (https://github.com/eightlimbed/betty-docker).

## Hosting
This Docker image is hosted on [Docker Hub](https://hub.docker.com/r/romalms10/pep8/) and is automatically updated when changes are made to it.

## How To Use
In your `Dockerfile` use `FROM romalms10/pep8` or use `docker pull romalms10/pep8`.

## Author
Robert Malmstein [<img src="https://user-images.githubusercontent.com/23224088/27935507-4e614b68-6260-11e7-8b20-d0352ef3ff53.png" height="18px"/>](https://twitter.com/RobertMalmstein)
