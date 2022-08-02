# docker-toolbox-aws

A docker toolbox image based on rewardenv/docker-toolbox with these additional tools included:
- awscli
- python3
- pip3

## Usage

```
docker run --rm -it rewardenv/docker-toolbox-aws bash
```

## Available tags

- latest, alpine-latest
- debian-bullseye-slim
- debian-buster-slim

## Build

```
DOCKER_BASE_IMAGE=debian:bullseye-slim bash -x scripts/build.sh

DOCKER_BASE_IMAGE=alpine:latest bash -x scripts/build.sh  
```
