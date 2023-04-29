# docker-nodejs-goals
# exercise of a simple nodejs application in docker

<!-- 
docker build .                                              -- runs the Dockerfile and creates an image
docker build -t name:tag                                    -- runs the Dockerfile and creates an named image
docker images                                               -- list images
docker rmi imageId                                          -- remove image
docker ps                                                   -- list active containers
docker ps -a                                                -- list all containers
docker rm containerID                                       -- delete a container
docker cp dummy/. containerID:/pathInsideContainer          -- copy a folder or file to the container 
docker cp containerID:/pathInsideContainer folder           -- copy a folder or file from the container to the current workfolder 
docker inspect imageID                                      -- inspect info inside the container
docker run -p 3000:80 -d --rm --name NewName containerID    -- runs a container on internal port 3000, external port 80 (set on code), detached from terminal (-d_), removing the container after end (--rm) and naming with NewName
-->
