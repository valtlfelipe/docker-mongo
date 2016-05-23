# docker-mongo [![Build Status](https://travis-ci.org/valtlfelipe/docker-mongo.svg?branch=master)](https://travis-ci.org/valtlfelipe/docker-mongo)

Docker Image based on the [latest Ubuntu image](https://hub.docker.com/_/ubuntu/), and latest MongoDB version 3.2.

Docker registry: [https://hub.docker.com/r/valtlfelipe/mongo/](https://hub.docker.com/r/valtlfelipe/mongo/).

Running:
```
docker pull valtlfelipe/mongo
docker run -p 27017:27017 --name myContainer -d valtlfelipe/mongo --storageEngine wiredTiger
```
