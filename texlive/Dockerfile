FROM debian:stable

RUN apt-get update \
	&& apt-get install -y git inkscape libreoffice-core make texlive-full \
	&& apt-get purge -y '.*-doc$' \
	&& apt-get clean -y
