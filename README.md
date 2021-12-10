# Datahub Fork with custom UI elements

This repo is a fork of Datahub it is used to build our custom docker image for the datahub-frontend container.

**Prerequisites**

- Docker and docker-compose installed
- Files in this repo
## How to build the datahub-frontend container

Run the following command:

`docker build -t ghcr.io/raft-tech/datahub-frontend:master -f ./docker/datahub-frontend/Dockerfile .`

## How can I make UI changes and test them locally?

Please refer to the instructions [here](datahub-web-react/README.md)

## I need Datahub related info where can I find it?

Please refer to the [Datahub Readme](./ORG-README.md)
