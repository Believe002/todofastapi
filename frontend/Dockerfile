FROM node:16-alpine3.17

WORKDIR /app
COPY package* .
RUN npm install

COPY . .
ENTRYPOINT [ "npm","run","start" ]