# docker-compose
docker-compose file for jupyter. run jupyter environment  automatic 

#Hello guys ,

Here is a linux inbuilt jupyter(anaconda) which can be use through any LAN device using port forwarding

Here we not need to generate token again and again instead use password = 123456789 and run your jupyter on browser

steps:

1- pull this image using cmd :-

                             # docker pull vishu1807/jupyter_python:v1.0

2- for this automatic setup you have to install docker-compose first:

                            visit this site :-   https://docs.docker.com/compose/install/

3- after download the docker-compose.yml file simple run this command:

                           # docker-compose up -d
     
     this command automatic setup environmet for jupyter on port 4545 on your localhost

4- now open your's any browser at <localhost:4545> jupyter run
                                    <localhost> = your's base linux ip address
                                    
#############################################################################################################################

for manual setup visit :- https://hub.docker.com/r/vishu1807/jupyter_python

