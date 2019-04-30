# DOCKER-VERSION 1.10
FROM xcyxiner/loopback:8.9.0
MAINTAINER xcyxiner "xcyxiner@me.com"
COPY  sources.list /etc/apt/sources.list
RUN apt-get update
RUN apt-get install -y imagemagick ghostscript poppler-utils
RUN apt-get install -y graphicsmagick
expose  3000
