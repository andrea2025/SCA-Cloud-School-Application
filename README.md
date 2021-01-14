# H1 SCA-Cloud-School-Application
### H3 Documentation

1. Created a SCA-Cloud-School-Application repository
2. Cloned the repository 
3. Created and edited the index.html 
4. Created and edited the Dockerfile file to setup nginx webserver on ubuntu OS
5. Install docker desktop for mac
6. build docker by running "docker build -t sca-cloud-school ." to create the docker image
7. run the command "docker images" to check if the the image is created
8. run the container using using "docker run -p 5000:80 -d sca-cloud-school" which will map ngnix port  80 running on the container to the host on port 5000
9. To make changes to the dockerfile, stop the running docker container using "docker stop 57f00675f76c(which is the id of the container)" , build docker image and run the container again

docker hun link :andrea45/sca-cloud-school




