# Tags
> _Built from [`quay.io/ibm/ubuntu:20.04`](https://quay.io/repository/ibm/ubuntu?tab=info)_
-	`2.249.2` - [![Build Status](https://travis-ci.com/lcarcaramo/jenkins-server.svg?branch=main)](https://travis-ci.com/lcarcaramo/jenkins-server)

### __[Original Source Code](https://github.com/linux-on-ibm-z/dockerfile-examples/blob/master/Jenkins/Dockerfile)__

# Jenkins

![Jenkins Logo](https://raw.githubusercontent.com/docker-library/docs/3ab4dafb41dd0e959ff9322b3c50af2519af6d85/jenkins/logo.png)

Jenkins is an open source build automation tool.

[Wikipedia](https://en.wikipedia.org/wiki/Jenkins_(software))

# How to Use This Image

Use the following command to spin up a Jenkins container:

`docker run --name <container_name> -p <host_port>:8080 -d quay.io/ibm/jenkins:2.249.2`

Optionally, use a Docker volume for persistant storage:

`docker run --name <container_name> -p <host_port>:8080 -d -v <jenkins_volume>:/var/jenkins_home quay.io/ibm/jenkins:2.249.2`

# License

© Copyright IBM Corporation 2017, 2020.

LICENSE: [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)
