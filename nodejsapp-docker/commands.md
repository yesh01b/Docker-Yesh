## Build and Create Image
docker build .                 --- to build the code from the Root/working directory
docker run -p 3000:80 imageid  --- to create the image and listen on port 3000 for local host

## Start or Stop the Containers
docker start container name    --- to start the container
docker stop container name     --- To stop the container

## Other command
docker ps      --- To get the running container list
docker ps -a   --- to get all the container list