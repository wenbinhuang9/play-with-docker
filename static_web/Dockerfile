# Version :0.0.1

# actually, dockerfiel is a seris of instructions executed by workflow, it allows flexible configuration/

# in this dockerfile,  we create the original ubuntu image, and install nginx into the ubuntu by creating a new lay on the top of ubuntu image. 

# It is also more like a script to design each container, and the container can be reused for multiple times, what a wonderful design of docker, it allows the sofware to be aggregated together to design a more powerful software, and it is easy to use, maintain, release the engergy into maintain teh software, great!

FROM ubuntu:14.04
MAINTAINER Wenbin Huang "Wenbin9huang@gmail.com"
RUN apt-get update
RUN apt-get install -y ngin
RUN echo 'Hello World' > /usr/share/nginx/html/index.html
EXPOSE 80
