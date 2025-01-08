##  docker commande

Docker : 
- run docker image 
>  docker build -t welcome-app .

- liste of docker image
> docker images 

- docker on specific port 
>  docker run -p 5000:5000 welcome-app

- Displays a list of currently running Docker containers
> docker ps 

- Show all containers (active or not)
> docker ps -a

- Show only container IDs
> docker ps -q

- stop docker with ID docker
>  docker stop ID


- get docker image from docker hub 

> docker pull docker/getting-started

> docker run -d -p 80:80 docker/getting-started

> url : http://127.0.0.1/tutorial/


- docker remove image 
>  docker image rm -f  welcome-app

-build docker image with tag
> docker build -t yaropaul/welcome-app .
-  change docker image name by tag
> docker tag yaropaul/welcome-app   yaropaul/welcome-app1

- run docker with docker hub account 
> docker login
> docker push yaropaul/welcome-app:latest
> docker run -d -p 5000:5000 yaropaul/welcome-app:latest


 Docker compose 
- run docker compose file 
> docker  compose up 

- stop  current running
> docker compose stop 
