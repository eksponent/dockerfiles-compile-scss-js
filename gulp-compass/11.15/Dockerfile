FROM node:11.15-stretch

RUN apt-get update
RUN npm install -g npm
RUN npm install -g gulp-cli

RUN apt-get install ruby-dev -y

RUN gem update
RUN gem install sass
RUN gem install sass-globbing
RUN gem install compass