Apicurio Studio
===============

## Usage

To start up Apicurio Studio

    docker run -it apicurio/apicurio-studio

You may want to map the port(s) so you can access the app

    docker run -it -p 8080:8080 apicurio/apicurio-studio

## Building the image

    docker build -t="apicurio/apicurio-studio" --rm .

## Image accessible on Docker hub

This image is automatically built and published into [Docker Hub](https://registry.hub.docker.com/u/apicurio/apicurio-studio/).

