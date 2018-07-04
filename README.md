PHP in Docker
=========================
A personalized build to run PHP in a containerized environment.

Installation
------------
```sh
$ docker pull auditemarlow/php
```

Usage example
-------------
```sh
$ docker run \
    --rm \
    --interactive \
    --name php \
    --volume "$PWD":/app \
    --workdir /app \
    auditemarlow/php:latest php "$@"
```
