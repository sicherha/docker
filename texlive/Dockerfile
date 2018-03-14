FROM debian:stable

RUN apt-get update \
	&& apt-get install -y dia git inkscape libreoffice make texlive-full \
	&& apt-get purge -y '.*-doc$' \
	&& apt-get clean -y
