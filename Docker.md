### 1. Check for all containers
docker ps -a
### 2. View all images
docker images
### 3. Run the container
docker run -d -p 5000:5000 imagename


### 4. Login to docker hub
docker login -u \<username\>
### 5. Push image to dockerhub
docker tag \<imagename\> \<username\>/\<repo-name\>

docker push \<username\>/\<repo-name\>

### 6. Pull image from dockerhu and run in interactive mode
docker pull \<imagename\>

docker run -it \<imagename\> /bin/bash

### 7. Create image from Docker file
docker build -t \<imagename\> \<dir\>

### 7. Create image from container
docker commit \<containername\> \<imagename\>
