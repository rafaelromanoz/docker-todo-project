FROM node:14-alpine AS todofront

WORKDIR /app

ADD ["./node_modules.tar.gz", "./"]

COPY ["./package.json", "./package-lock.json", "./"]

EXPOSE 3000
# Step 4
RUN ["npm", "install"]
# Step 5
COPY ["./", "./"]
# Step 6
ENTRYPOINT [ "npm", "start" ]