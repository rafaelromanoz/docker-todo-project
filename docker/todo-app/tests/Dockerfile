FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app

ADD ["./node_modules.tar.gz", "./"]

COPY ["./package.json", "./package-lock.json", "./"]

COPY ["./", "./"]

ENTRYPOINT [ "npm", "test" ]