This repository is for exploring docker images and containers while reading raps-with-r.dev

#build the docker image from the dockerfile
docker build -t raps_hello .

#enter the command line from within the docker container
docker run -it raps_hello /bin/bash

#run the bash command in the docker image
docker run --rm raps_hello uname -a

