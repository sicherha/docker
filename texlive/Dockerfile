FROM ubuntu:18.10

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update \
	&& apt-get install -y dia git inkscape libreoffice make python-pygments python3-matplotlib sqlite3 texlive-full unoconv \
	&& apt-get purge -y '.*-doc$' \
	&& apt-get clean -y
