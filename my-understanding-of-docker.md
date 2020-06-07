
What is docker? 

Docker is used for software packaging, shipping, and providing containner for image to be run. 

The emerge of docker makes it convenient for developers to build a testing environment quickly, improve the development efficiency. 

The dockerfile used to build an image is very powerful and flexible, it allows packaging different software into an image, and the image can be run in the containner, then developer can run the containner to do the test .

The basic objects of docker

the basic objects of docker is container, image and volume.

THe container is nothing more than a process, it is light-weight, easy to create, fast to create, and very efficient. 

The image is nothing more than a file, we can use dockerfile to design powerful and flexible softwares. 

The volums is nothing more than a storage  used to enable container to read or write data from the volume. 

Container VS Image

Container is dynamic, while the image is static. THe image has to run on the container, whie container can't run without image.  Contianer is a collections of visual  hardware resources such as cpu, memory, network, graphical hardware, which is used to run image. While image is a file packaging the multiple softwares and configurations.  The image can be build, udpate and shipped. 

The architecture of docker.

According to the docker objects, container, volume and image. The architecture can be seperated into three parts. 

The docker architecture is a classical client-server architecture. 

The is a server with daemon process to accept HTTP request. While the client is responsible for getting request from the client. One of interface is the commandline provided by docker. When user invokes the commandlines, the commandline will be pushed to the docker client to get the service.


The container is managed by Docker Daemon server, the Docker Daemon server is responsible for the management of container creation, stop, start, deletion.  The docker Daemon server is nothing more than visual management of resources of hardware, it request the isolated resources from the underlinging operating system. 

The image module is repsonsible for the mangaement of image build ,deletion , and provide repositry to make it convenitent pull or push the image from or into repositroy. ANd it also provides creation of personal repositry. 

The techniques behind image is that it uses layer and merging the filesystem into a file .  


Docker and test 

How we can make full use of docker to do development test? 
