## Build and Create Image
docker build -t node:volume .                 --- to build the code from the Root/working directory with name and tag of the image
docker run -p 3000:80 -d --rw --name node-volume -v feedback:/app/feedback -v localprojectpath(D:\yesh\docker\Docker-Yesh\node-feedback-data):/app -v /app/node_modules imageid  --- to create the image and listen on port 3000 for local host in detached mode, remove automatically when it is stopped stage, name of the container is node.Creates a named volume which will store data and be available even container stopped or removed. Also mount local path to the conatiner without any issue

## Start or Stop the Containers
docker start container name    --- to start the container
docker stop container name     --- To stop the container

## Other command
docker ps      --- To get the running container list
docker ps -a   --- to get all the container list

## Volume command
docker volume ls    -- To list all the volumes avaialble

## logs
docker logs containername   -- To view the logs of the container