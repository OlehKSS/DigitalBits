# Installation Instructions for Docker build  

Use docker to build the app:
```shell
docker build -t digitalbits-core:latest .
```
and then you can check the app by running:
```shell
docker run --rm digitalbits-core:latest digitalbits-core version
```