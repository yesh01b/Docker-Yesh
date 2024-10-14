## Build and Create Image
docker build -t python:test .               --- to build the code from the Root/working directory with name python and tag test
docker run -it --name python python:test    --- to create the image and run the code in interactive mode to enter the vales with container name python.

## Start or Stop the Container
docker start -a -i container name or docker -i  container name --- to start the container in interacitve mode
docker stop container name                                     --- To stop the container

## Other command
docker ps      --- To get the running container list
docker ps -a   --- to get all the container list