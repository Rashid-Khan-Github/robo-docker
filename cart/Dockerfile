FROM node:14.21.3-alpine
EXPOSE 8080
WORKDIR /opt/server
COPY package.json .
COPY server.js .
RUN npm install
CMD [ "node", "server.js" ]