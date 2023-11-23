# pocketbase
Pocketbase Container for H0wlit.

# Installation

1. download docker per their [instructions]("https://docs.docker.com/engine/install/").
2. build docker image with:
```
docker build -t "h0wlit/pocketbase" .
``` 
3. run docker container with:
```
docker run -it --rm -p 8090:8090 h0wlit/pocketbase
```
This makes the container run on port 8090 of the localhost.

## URLs


admin URL: http://localhost:8090/_/ \
api URL:   http://localhost:8090/api/

# Pulling image

You could also use the docker image as is without pulling the github repo. To do this use 
```
docker pull h0wlit/pocketbase 
```
and then you can run step 3. of Installation to run the container  

# Using the image in a Docker Compose ```compose.yml``` file.

