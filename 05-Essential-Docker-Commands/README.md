# Docker - Essential Commands
- The below are the list of essential commands we are in need 

|     Commands                 |    Description                                  |
| ------------------------------- | --------------------------------------------- |
| docker ps | List all running containers |
| docker ps -a | List all containers stopped, running |
| docker stop container-id | Stop the container which is running |
| docker start container-id | Start the container which is stopped |
| docker restart container-id | Restart the container which is running |
| docker port container-id | List port mappings of a specific container |
| docker rm container-id or name | Remove the stopped container |
| docker rm -f container-id or name| Remove the running container forcefully |
| docker pull image-info | Pull the image from docker hub repository |
| docker pull stacksimplify/springboot-helloworld-rest-api:2.0.0-RELEASE | Pull the image from docker hub repository |
| docker exec -it container-name /bin/sh | Connect to linux container and execute commands in container |
| docker rmi image-id | Remove the docker image |
| docker logout | Logout from docker hub |
| docker login -u username -p password | Login to docker hub |
| docker stats | Display a live stream of container(s) resource usage statistics |
| docker top container-id or name | Display the running processes of a container |
| docker version | Show the Docker version information |
| docker push account/image-name | Push a docker image to docker hub |
| docker images | List available images |
| docker tag  josueqxd/nginx-basic:v1 josueqxd/nginx-basic:v1-release | Example on how to create a copy from a image with different version |
| docker images | List available images |
| sudo docker OPERATION $(sudo docker ps -a -q) | Made operation on all dockers |
| sudo docker run --name mynginx1 -p 82:80 -d josueqxd/nginx-basic:v1 | Example on how to start a docker container on port 82 |