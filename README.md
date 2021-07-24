#  SCA Cloud School Application
###  Documentation

* Created a SCA-Cloud-School-Application repository  

* Cloned the repository 
* Installation of docker into my local system
* Created and edited the index.html file
* Created and edited the Dockerfile file to setup nginx webserver on ubuntu OS

#### On the cli
* build docker by running `docker build -t sca-cloud-school .` to create the docker image.
* run the command "docker images" to check if the the image is created
* run the container using using `docker run -p 3000:80 -d sca-cloud-school` which will map ngnix port  80 running on the container to the host on port 3000

#### To Test the Application
* Go to your web browser, type in "localhost:3000", the webpage created will read: "Welcome to SCA Cloud School Application"

#### push changes to git
From command prompt, create a branch named “Start using "git checkout -b Start
* run "git add ."
* run 'git commit -m `first sca`
* run "git push origin Start`

#### To Make Changes to the Dockerfile
 * stop the running docker container using `docker stop 57f00675f76c(which is the container ID)`
 * build docker image and run the container again using "docker run -p 3000:80 -d sca-cloud-school"
 
 #### To Test the Application
* Go to your web browser, type in "localhost:3000", the webpage created will read: Welcome to SCA Cloud School Application , this is my first assessment

#### push changes to git
From the cli , create a branch named "feature" using "git checkout -b feature"
* run "git add ."
* run 'git commit -m `sca text updated`
* run "git push origin feature”
* create a pull request and merge feature into Start

#Docker hub repo (https://hub.docker.com/repository/docker/andrea45/sca-school)
