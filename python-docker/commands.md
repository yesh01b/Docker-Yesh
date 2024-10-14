## Build and Create Image
docker build .     --- to build the code from the Root/working directory
docker run -it     --- to create the image and run the code in interactive mode to enter the vales

## Start or Stop the Container
docker start -a -i  or docker -i  --- to start the container in interacitve mode
docker stop container name        --- To stop the container

## Other command
docker ps      --- To get the running container list
docker ps -a   --- to get all the container list