# Commands
--------------
## Contents

#### 1. [Linux - Ubuntu](#anch1)
#### 2. [Networking](#anch2)
#### 3. [Docker](#anch3)
#### 4. [Windows](#anch4)


<a name="anch1">**1. Linux - Ubuntu**</a>

1. To update ubuntu OS `apt-get update`

2. To install package `apt-get install <packageName>`

3. To install VIM - text editor
`apt install vim`
`ESC+: then q+!+ENTER` // to exit from vim

4. To find application/program -- `which <programName>`

5. To find application/program in broader range of system directories -- `whereis <programName>`

6. For viewing files that are not very long; it does not provide any scroll-back -- `cat <fileName>`

7. To print first 15 lines of the file -- `head <fileName>`

8. To print last 10 lines of the file -- `tail <fileName>`

9. To go to home directory -- `cd` or `cd ~`

10. To go to parent directory -- `cd ..`

11. Change to previous directory -- `cd -`

12. Used to look at a file backwards, starting with the last line -- `tac <fileName>`

13. Used to view larger files because it is a paging program -- `less <fileName>`

14. Touch is used to create empty file and change the file settings 
 
 To create an empty file -- `touch <fileName>` 
 
 To change time stemp in file -- `touch -t 12091600 myfile` This sets the myfile file's timestamp to 4 p.m., December 9th (12 09 1600)
 
 15. To remove the file `rm <fileName>`
 
 16. To remove the file forcefully `rm -f <fileName>`
 
 17. To Interactively remove a file `rm -i <fileName>`
 
 18. To rename the file `mv <fileName>`
  


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



<a name="anch4">**4. Windows**</a>

1. To get path list in command prompt -- `path` or `%path:;=&echo.%`


