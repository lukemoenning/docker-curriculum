# Docker Curriculum


## Notes
docker run x -> runs “x” <br />
docker stop x -> stop “x” <br />
docker pull x -> pull “x” <br />
docker push x -> push “x” <br />

docker rm -> removes container <br />
docker container prune -> removes all containers

docker rmi -> removes image

docker ps -> displays containers <br />
docker ps -a -> display all containers


docker run
-it -> interactive terminal, can kill with ctrl-c <br />
—rm -> auto remove container when it exits <br />
-d -> detached terminal <br />
—name x -> give the name “x” <br />
-P -> publish all exposed ports to random ports <br />
-p x -> publish to port “x" <br />


## Run on localhost:8888

$ docker pull lukemoenning/catnip <br />
$ docker run -p 8888:5000 lukemoenning/catnip <br /> <br />

