FROM debian:stable

RUN apt update \
	&& apt install -y git inkscape make texlive-full \
	&& apt purge -y '.*-doc$' \
	&& apt clean -y
