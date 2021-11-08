FROM node:alpine

ADD ["./node_modules.tar.gz", "./"]

COPY ["./package*.json",  "./"]

EXPOSE 3001

RUN ["npm", "install"]

COPY ["./", "./"]

ENTRYPOINT [ "npm","start" ]