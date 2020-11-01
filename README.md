## Docker image for CI

https://hub.docker.com/r/fordnox/docker-builder-ci

`docker pull fordnox/docker-builder-ci`

Installed

* git
* node
* npm
* make
* ant
* php 7.4
* composer

Example run

    docker run --rm --mount type=bind,source=$(pwd),target=/opt -w /opt fordnox/docker-builder-ci make