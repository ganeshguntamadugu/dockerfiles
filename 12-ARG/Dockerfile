ARG version
FROM almalinux:${version:-9}
# FROM instruction is the first instruction in Dockerfile. It represents base OS.

ENV Name="Ganesh" \
    Age=25

RUN echo "My name is $Name, I'm $Age years old"

CMD [ "sleep", "100" ]