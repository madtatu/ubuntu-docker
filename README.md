ubuntu-docker
=============

Docker image based on Ubuntu 14.04 (trusty) with 
- with apache 2.4 webserver installed
- with nodejs 0.10.25 

This image is using the ubuntu:14.04 image as base image.


### Installation
```sh
$ docker pull madtatu/ubuntu-docker
```

### Usage
```sh
$ docker run -v /document/root/on/your/mahine:/var/www -p 8080:80 madtatu/ubuntu-docker
```

The webserver will be available on TCP port 8080 on your machine. The document root will be the folder you specified after the -v switch.
