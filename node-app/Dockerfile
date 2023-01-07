FROM node:18-alpine3.16
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY node-app/app/. /usr/src/app
RUN npm install
CMD [ "node", "server.js" ]
