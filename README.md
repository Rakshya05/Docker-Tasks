
# Docker
This repository contain an task for learning docker.

## Prequistics

Install docker in your devices.

Take reference from https://docs.docker.com/engine/install/

```bash
  #!/bin/bash

# Install Docker on a Linux machine
sudo apt update
sudo apt install -y docker.io
```
## Task 1 : Pull image from Dockerhub 

Suppose, we have to pull Nginx image from Dockerhub

1. Copy command from Dockerhub
```bash
 docker pull nginx
 ```

2. Check if nginx image is pulled or not.
```bash
 sudo docker images
 ```
3. To run pulled docker image nginx in demon mode
```bash
 sudo docker run -d -p 8085:80 nginx
 ```
4. To see running processes
```bash
 sudo docker ps
 ```
Nginx is running in http://0.0.0.0:8085/


## Screenshot
https://docs.google.com/document/d/1jp9VFP8yFcYB1Scc1Q2MVUxxc-4kt7qdEdo3j70V3Dw/edit?usp=sharing
