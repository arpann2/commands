# Commands
--------------
## Contents

#### 1. [Linux - Ubuntu](#anch1)
#### 2. [Networking](#anch2)
#### 3. [Docker](#anch3)



<a name="anch1">**1. Linux - Ubuntu**</a>

1. To update ubuntu OS `apt-get update`

2. To install package `apt-get install <packageName>`

3. To install VIM - text editor
`apt install vim`
`ESC+: then q+!+ENTER` // to exit from vim





<a name="anch2"> **2. Networking**</a> 

1. Get DNS info -- `nslookup` Eg. `nsloopup google.com`

2. To find out how many hops and travel time to reach packets, and how many servers involved -- `tracert` 
Eg. `tracert cnn.co.jp` -- it is called trace root command





<a name="anch3">**3. Docker**</a>

1. List of images -- `docker images`

2. List of currently running containers -- `docker ps` ps stands for process status
`docker ps -a`

3. Remove docker image forcefully if image is not getting removed -- `docker rmi -f <imageName:Tag>`

4. Start docker container -- `docker run -it <imageName>`
       
5. Run and Map local port to docker container port -- `docker run -dit -p 80:80 <imageName:imageTag> /bin/bash` 
>this will connect local host port 80 to docker container port 80

6. Verify ports are mapped and docker is running -- `docker ps`

7. To go into specific container --    `docker exec -it <containerId> bash`

8. To come out from docker Container -- `CTRL+p+q`



