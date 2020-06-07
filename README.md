# play-with-docker

A demo for docker

# Architecture of docker 


# Some easy-to-use docker command line

## Command line of container

docker run -t -i --name mydockernmae  untuntu:version number some parameters, docker run will download image for repo, and then create a container.

docker start  dockername or dockerid

docker attach dockername or dockerid,  attach the current window to the docker output or docker command line 

docker stop dockername or dockerid

docker ps -a , get to know how many containers are there

docker inspect dockername or dockerid, get to know more details about the docker.

docker rm dockername or dockerid, delete the container

## Command line of image management

docker pull fedora
