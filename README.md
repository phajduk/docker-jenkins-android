# Commands
Stop container jenkins-master

`docker stop jenkins-master`

Create container from image myjenkins

`docker run -p 8080:8080 --name=jenkins-master -d myjenkins`

Create image myjenkins from current directory which contains Dockerfile

`docker build -t myjenkins .`

Delete created image

`docker rmi myjenkins`

# Listing
List available images

`docker images`

List current containers

`docker ps -a`

