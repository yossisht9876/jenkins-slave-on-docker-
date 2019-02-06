# jenkins-master and slave-on-docker
jenkins dockerfile + jenkins slave docker file = docker-compose after the build

images are with docker and ansible instelled


usege:

1. build the images with tags:

docker build -t <nameoftheimage> .

2. run the compose file in oredr to run the containers

docker-compose up -d
