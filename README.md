# kubernetes
## About the project :
- music-deploy.yml:

image from dockerhub: https://hub.docker.com/r/yanivomc/spring-music and using ClusterIP deploy

- ingress.yml :

Ingress can access to spring-music from http://127.0.0.1/music.


## in order to run the project:
- clone this repository 
- run from terminal: kubectl apply -f music-deploy.yml && kubectl apply -f ingress.yml 
 
 http://127.0.0.1/music

