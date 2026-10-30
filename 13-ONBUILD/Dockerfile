FROM almalinux
# FROM instruction is the first instruction in Dockerfile. It represents base OS.
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html

ONBUILD COPY index.html /usr/share/nginx/html/index.html
# This ONBUILD instruction runs only, when any user uses your image

CMD [ "nginx", "-g", "daemon off;" ]
# CMD instruction runs at the time of container creation. CMD can be overridden at runtime