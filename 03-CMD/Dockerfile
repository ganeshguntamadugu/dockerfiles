FROM almalinux
# FROM instruction is the first instruction in Dockerfile. It represents base OS.

RUN dnf install nginx -y
# RUN instruction is used to configure image. Runs at the time of image building

CMD [ "nginx", "-g", "daemon off;" ]
# CMD instruction runs at the time of container creation