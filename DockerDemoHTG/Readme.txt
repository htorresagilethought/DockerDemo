
list containers
docker ps -a

delete container
docker rm <containerid>

Create an Docker image for the project using port 85 for the container.
docker run --name  test1 -p  8080:85 dockertraining2020/dockerdemohtg

Create a Docker Container using the image. Assign "Site1" as container name and port "8085" to run the container.
docker run --name  Site1 -p  8085:80 dockertraining2020/dockerdemohtg

Create a Docker Container using the image. Assign "Site2" as container name, port "8086" and "storename" as "Plano".
docker run --name  Site2 -p  8086:80 dockertraining2020/dockerdemohtg

Upload the image to Docker Hub using the following credentials:
https://hub.docker.com/repository/docker/dockertraining2020/dockerdemohtg
