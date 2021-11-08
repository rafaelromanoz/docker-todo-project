FROM node:14-alpine

WORKDIR /app

ADD ["./node_modules.tar.gz", "./"]

COPY ["./package.json", "./package-lock.json", "./"]

EXPOSE 3000

COPY ["./", "./"]

ENTRYPOINT [ "npm", "start" ]