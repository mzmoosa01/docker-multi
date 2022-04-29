# Docker-multi tutorial exercise

This is a simple react project created to learn how to run multiple applications using docker. It was created under the guidance of 
[Steven Grider's Udemy course](https://www.udemy.com/course/docker-and-kubernetes-the-complete-guide/?src=sac&kw=docker+kubernetes+complete)

# Getting started

You can test and get the application up and running by simply running docker-compose: 

``` docker-compose up ```
 
 or by using Docker run 

```
docker build -t <image-tag> -f Dockerfile.dev
and then
docker run <image-tag>
```
