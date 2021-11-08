FROM node:14-alpine

WORKDIR /usr/src/app
ADD ["./node_modules.tar.gz", "./"]

COPY ["./package*.json",  "./"]

ENV REACT_API_HOST: todobackend

ENV REACT_APP_PORT: 3001

EXPOSE 3001

RUN ["npm", "install"]

COPY ["./", "./"]

ENTRYPOINT [ "node","." ]