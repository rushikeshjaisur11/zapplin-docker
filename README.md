# zapplin-docker
Zapplin notebook on docker container

This is initial version of docker compose file. There are some assumptions while composing this file :
* Spark must be installed at "C:\\spark" folder 
* Initial version uses spark's default config, spark config folder will be added in next version.

Steps to compose docker file : 
* Step 1 : Install docker for windows 
* Step 2 : After installing docker clone the repo
* Step 3 : copy repo in any path or rename folder (E.g copy in C drive and rename it as zapplin)
* Step 4 : Create the logs and notebook folder if not present already.
* Step 5: Open command prompt in the zapplin folder and use below command to compose docker file : 
<br>
 <b><div>docker compose -f docker-compose.yaml up -d </div></b>

* Command will install required docker images and setup the zapplin notebook
* After command finishes you can access zapplin notebook:
* * <div> Zapplin : localhost:8080</div>
* * <div> Spark UI : localhost:4040</div>





