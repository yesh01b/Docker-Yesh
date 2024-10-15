## Build and Create Image
docker build -t node:volume .                 --- to build the code from the Root/working directory with name and tag of the image
docker run -p 3000:80 -d --rw --name node-volume imageid  --- to create the image and listen on port 3000 for local host in detached mode, remove automatically when it is stopped stage, name of the container is node

## Start or Stop the Containers
docker start container name    --- to start the container
docker stop container name     --- To stop the container

## Other command
docker ps      --- To get the running container list
docker ps -a   --- to get all the container list

## Volume command
docker volume ls    -- To list all the volumes avaialble