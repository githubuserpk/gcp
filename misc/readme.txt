#install docker
sudo yum -y update
sudo yum install -y docker
docker --version

#this command lists the docker images, if there are no images, it returns nothing
docker images

#list the available containers
docker ps

#to run a image
docker run <image_name>

#to run hello-world image, if it is not there it will pull the image from docker hub and run it
docker run hello-world

#now, docker images shows the output
docker images 

#start and stop docker
sudo service docker start
sudo service docker stop

#remove docker from the system
sudo yum remove -y docker
