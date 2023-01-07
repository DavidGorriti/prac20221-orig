FROM node:18-alpine3.16
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY app/. /usr/src/app
RUN npm install
CMD [ "node", "server.js" ]
