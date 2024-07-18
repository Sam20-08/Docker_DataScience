# Docker_DataScience
1.To Build docker image
* docker build -t app-name
  
2.To check if docker images are available
* docker images
  
3.To run the container
* Docker run -p host_port:container_port app name
  
4.To rename a repository for the container
* docker images rm -f app_name
* docker tag existing_name  new _name
  
5.To push the files to docker hub
* doker push username/appname the username is not necessary

What is docker image?
* It contains all the instruction and components needed to run a specific application
* It is a blue print that defines everything the application needs

What is docker-compose?
* Docker compose is a tool for defining and running multi container docker applications
* docker-compose.yaml has the configuration for different containers
