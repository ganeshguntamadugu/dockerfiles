FROM almalinux
# FROM instruction is the first instruction in Dockerfile. It represents base OS.

RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
# RUN instruction is used to configure image. Runs at the time of image building

CMD [ "nginx", "-g", "daemon off;" ]
# CMD instruction runs at the time of container creation

LABEL Name="Ganesh" \ 
      Age=25 \ 
      Roel="DevOps"
# LABEL instruction is used to add metadata and to filter the images

EXPOSE 8080 
# EXPOSE instruction doesn't actually publish the port, it is used to let the users know what are the ports this container will open.

ENV user="gana" \
    rollno=23 \
    education="graduate"
# ENV instruction is used to sets the environment variables, these can be used inside the container.

# COPY index.html /usr/share/nginx/html/index.html
# COPY instruction is used to copy files from local to image.
    
ADD https://raw.githubusercontent.com/ganeshguntamadugu/dockerfiles/refs/heads/main/01-FROM/Dockerfile /usr/share/nginx/html/index.html
# ADD instruction also does same as copy, but it has 2 extra capabilities
# 1. It can get files from internet
# 2. It can extract the files into image

RUN chmod +r /usr/share/nginx/html/index.html
