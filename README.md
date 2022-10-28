# Docker Curriculum


## Notes
docker run x -> runs “x”
docker stop x -> stop “x”
docker pull x -> pull “x”
docker push x -> push “x”

docker rm -> removes container
docker container prune -> removes all containers

docker rmi -> removes image

docker ps -> displays containers
docker ps -a -> display all containers


docker run
-it -> interactive terminal, can kill with ctrl-c
—rm -> auto remove container when it exits
-d -> detached terminal 
—name x -> give the name “x”
-P -> publish all exposed ports to random ports
-p x -> publish to port “x"


## Run on localhost:8888

$ docker pull lukemoenning/catnip <br />
$ docker run -p 8888:5000 lukemoenning/catnip <br /> <br />

