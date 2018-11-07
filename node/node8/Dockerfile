# DOCKER-VERSION 1.10

FROM node:8.9.0

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
RUN apt-get update
RUN apt-get install -y imagemagick
RUN npm install -g cnpm --registry=https://registry.npm.taobao.org
RUN cnpm install -g strongloop
RUN cnpm install -g pm2
expose  3000
