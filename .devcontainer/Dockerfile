FROM node:20

WORKDIR /app

# install & enable fish shell
RUN apt-get update && apt-get install -y fish
RUN chsh -s /usr/bin/fish

# print versions
RUN node --version

# install firebase cli
RUN npm install -g firebase-tools

# install java
RUN apt install -y default-jre