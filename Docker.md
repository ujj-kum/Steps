### 1. Check for all containers
docker ps -a
### 2. View all images
docker images
### 3. Create image from Docker file
docker build -t \<imagename\> \<dir\>

### 4. Create image from container
docker commit \<containername\> \<imagename\>

### 5. Run the container
docker run -d -p 5000:5000 imagename


### 6. Login to docker hub
docker login -u \<username\>
### 7. Push image to dockerhub
docker tag \<imagename\> \<username\>/\<repo-name\>

docker push \<username\>/\<repo-name\>

### 8. Pull image from dockerhu and run in interactive mode
docker pull \<imagename\>

docker run -it \<imagename\> /bin/bash

### Pushing image to Azure Container Registry
docker build --tag \<loginserver\>/\<imagename\>:tagname

docker login \<loginserver\>
use username and password

docker push \<loginserver\>/<imagename>


