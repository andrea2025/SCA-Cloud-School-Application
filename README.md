#  SCA-Cloud-School-Application
###  Documentation

1. Created a SCA-Cloud-School-Application repository  

2. Cloned the repository 
3. Created and edited the index.html 
4. Created and edited the Dockerfile file to setup nginx webserver on ubuntu OS
5. Installation of docker
#### On the cli
* build docker by running `docker build -t sca-cloud-school .` to create the docker image.
* run the command "docker images" to check if the the image is created
* run the container using using `docker run -p 5000:80 -d sca-cloud-school` which will map ngnix port  80 running on the container to the host on port 5000
#### To Test the Application
* Go to your web browser, type in "localhost:5000", the webpage created will read: "Welcome to SCA Cloud School Application"
#### push changes to git
From command prompt, create a branch named "stable" using "git checkout -b stable"
* run "git add ."
* run 'git commit -m `First Commit`
* run "git push `--set-upstream origin stable`

#### To Make Changes to the Dockerfile
 * stop the running docker container using `docker stop 57f00675f76c(which is the container ID)`
 * build docker image and run the container again using "docker run -p 5000:80 -d sca-cloud-school"

10.pushing docker image to docker hub, using the command prompt
* Login into docker hub using the cli
* Create the image using `docker tag <image> <username>/<repository>`
* Push the image to docker hub `docker push <username>/<tagname>`
* Run the container with `docker run -p 8000:80 -d andrea45/sca-cloud-school`


## docker hub repository - https://hub.docker.com/repository/docker/andrea45/sca-cloud-school

