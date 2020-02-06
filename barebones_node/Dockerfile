FROM ubuntu:latest
# ubuntu setup
RUN apt-get update -y
RUN apt-get upgrade -y 
RUN apt-get install nodejs -y && apt-get install npm -y  
RUN apt-get install curl wget gnupg2 -y --fix-missing


# set VM env
ENV VM=true

# obtain latest stable version of node
RUN npm cache clean -f
RUN npm install -g n
RUN n stable 
