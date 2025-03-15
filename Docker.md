### 1. Check for all containers
docker ps -a
### 2. View all images
docker images
### 3. Run the container
docker run -d -p 5000:5000 imagename


### Login to docker hub
docker login -u <username>
### Push image to dockerhub
docker tag <imagename> <username>/<repo-name>
docker push <username>/<repo-name>
