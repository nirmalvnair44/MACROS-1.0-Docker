# MACROS-1.0-Docker

#### `Systems`, `Docker`
Mentors
1. [@namanmanish](https://github.com/namanmanish) (+91 9429504960)
2. [@narayanpai1](https://github.com/narayanpai1) (+91 9108074459)


### Problem Statement
Containerised MVC web app with the help of docker

### Description
- Use any MVC framework (rails,django,Nodejs) and connect it to mysql
- You should pull the mysql image from the docker-hub 
- For the framework write a dockerfile and then build the image
- Run this two containers and create a network to facilitate their communication
- For the mysql container use volumes so that you can retain the data
- Create a  docker-compose.yml file which will spin up these two containers and also help with the configurations

### Useful Resources
1. [Docker Tutorial for Beginners](https://youtu.be/3c-iBn73dDE)
2. [Overview of Docker Compose](https://docs.docker.com/compose/)

### Bonus
Use bind-mounts to debug while the container is running. Point your base folder of your project from your host os to the base folder inside the container
