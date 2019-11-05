# Commands
--------------
## Contents

#### 1. [Linux - Ubuntu](#anch1)
#### 2. [Networking](#anch2)
#### 3. [Docker](#anch3)



<a name="anch1">1. Linux - Ubuntu</a>

To update ubuntu OS `apt-get update`

To install package `apt-get install <packageName>`

To install VIM - text editor
`apt install vim
ESC+: then q+!+ENTER // to exit from vim
`


<a name="anch2"> 2. Networking</a> 

Get DNS info -- nslookup` Eg. `nsloopup google.com`

To find out how many hops and travel time to reach packets, and how many servers involved -- `tracert` 
Eg. `tracert cnn.co.jp` -- it is called trace root command

<a name="anch3">3. Docker</a>

List of images -- `docker images`

List of currently running containers -- `docker ps` ps stands for process status
`docker ps -a`

Remove docker image forcefully if image is not getting removed -- `docker rmi -f <imageName:Tag>`

Start docker container -- `docker run -it <imageName>`
       
Run and Map local port to docker container port -- `docker run -dit -p 80:80 <imageName:imageTag> /bin/bash` this will connect local host port 80 to docker container port 80

Verify ports are mapped and docker is running -- `docker ps`

To go into specific container --    `docker exec -it <containerId> bash`

To come out from docker Container -- `CTRL+p+q`



