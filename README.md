# jenkins_docker_containers

How to create, push and pull docker containers on dockerhub.

## Prerequisites

Installed:
1. docker http://docker.io/

## Getting Started

We have Created:
1. account luxoftsdl on http://hub.docker.com
2. repositories for each image
  -  luxoftsdl/jenkinsci          - for jenkins master
  -  luxoftsdl/jenkins-agent:v0.1 - for jenkins nodes

### Create image
```
docker tag my_image luxoftsdl/jenkinsci:2.67
```
### Login to hub.docker.com
```
docker login
```
### Push
```
sudo docker push luxoftsdl/jenkinsci
```
### Pull
```
docker pull luxoftsdl/jenkinsci
```



