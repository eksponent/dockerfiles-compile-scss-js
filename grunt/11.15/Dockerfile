FROM node:11.15-stretch

RUN apt-get update
RUN apt-get install ruby ruby-sass -y
RUN npm install -g npm
RUN npm cache clear --force
RUN npm install -g grunt-cli
