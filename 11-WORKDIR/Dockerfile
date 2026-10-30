FROM almalinux
# FROM instruction is the first instruction in Dockerfile. It represents base OS.

RUN mkdir /tmp/docker
# RUN instruction is used to configure image. Runs at the time of image building

WORKDIR /tmp/docker
# WORKDIR is used to set the current working directory inside docker image

RUN echo "Hello Docker" > hello.txt

CMD [ "sleep", "100" ]
# CMD instruction runs at the time of container creation