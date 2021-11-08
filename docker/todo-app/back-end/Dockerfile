FROM node:14-alpine

WORKDIR /usr/src/app

ADD ["./node_modules.tar.gz", "./"]

COPY ["./package*.json",  "./"]

EXPOSE 3001

RUN ["npm", "install"]

COPY ["./", "./"]

ENTRYPOINT [ "npm","start" ]