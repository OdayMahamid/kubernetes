# kubernetes
## About the project :
- music-deploy.yml:

image from dockerhub: https://hub.docker.com/r/yanivomc/spring-music and using ClusterIP deploy

- ingress.yml :

Ingress can access to spring-music from http://127.0.0.1/music.


## in order to run the project:
- clone this repository 
- run from terminal: kubectl apply -f music-deploy.yml && kubectl apply -f ingress.yml 
- access to http://127.0.0.1/music

![68747470733a2f2f696d6775722e636f6d2f4442474265506a2e706e67](https://user-images.githubusercontent.com/58177069/137948299-bcc52366-b9c8-4a05-8cbe-6d8306725e12.jpeg)

