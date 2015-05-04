## Docker Riemann Dockerfile

This repository contains **Dockerfile** of [Riemann](http://riemann.io/) for [Docker](https://www.docker.com/) [automated build](https://registry.hub.docker.com/u/cogniteev/riemann/) published to the public [Docker Hub Registry](https://registry.hub.docker.com/).

### Base Docker Image

* [cogniteev/oracle-java:java8](https://registry.hub.docker.com/cogniteev/oracle-java)

### Installation

1. Install [Docker](https://www.docker.com/)

2. Download [automated build](https://registry.hub.docker.com/u/cogniteev/riemann/): `docker pull cogniteev/riemann`

### Usage

    docker run cogniteev/riemann

* Exposed ports are 5555 and 5556
* Default Riemann configuration is located in `/usr/share/riemann-0.2.9/etc/riemann.config` directory. You are modify its content or mount a volume to replace the default configuration.

### License

The `cogniteev/riemann` image is licensed under the Apache License, Version 2.0. See LICENSE for full license text.
