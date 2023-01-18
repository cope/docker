FROM ubuntu:20.04

ENV DEBIAN_FRONTEND noninteractive

# Initial Ubuntu setup
RUN apt update \
	&& apt install -y curl git sshpass \
	&& apt-key update \
	&& rm -rf /var/lib/apt/lists/*

# NodeJS & code-complexity
RUN apt update \
	&& curl -sL https://deb.nodesource.com/setup_18.x -o nodesource_setup.sh \
	&& bash nodesource_setup.sh \
	&& apt -y install nodejs \
	&& npm i -g code-complexity esprima \
	&& rm -f nodesource_setup.sh \
	&& rm -rf /var/lib/apt/lists/*
