Look in phase 1 dockerfile for info

docker build -t abc/deep-dive-phase-1 .
docker container run -p 8080:80 --name deep1 -d abc/deep-dive-phase-1


docker container run -p 8081:80 --name deep2 -d abc/deep-dive-phase-2
