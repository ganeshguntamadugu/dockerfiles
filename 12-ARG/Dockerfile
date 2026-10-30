ARG version
FROM almalinux:${version:-9}
# FROM instruction is the first instruction in Dockerfile. It represents base OS.

ARG Name="Ganesh" \
    Age=25

ENV name=$Name

RUN echo "My name is $Name, I'm $Age years old"

CMD [ "sleep", "100" ]
# CMD instruction runs at the time of container creation. CMD can be overridden at runtime