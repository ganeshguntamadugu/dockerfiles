FROM almalinux
# FROM instruction is the first instruction in Dockerfile. It represents base OS.

RUN useradd expense
# RUN instruction is used to configure image. Runs at the time of image building

USER expense
# For security you should not run containers using root user, it must be on normal user. Atleast last instruction should USER <some-username>

CMD [ "sleep", "100" ]
# CMD instruction runs at the time of container creation

