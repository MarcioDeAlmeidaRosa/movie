FROM node:16-alpine

EXPOSE 8181

 WORKDIR /app

 COPY package*.json .

 RUN npm install

 COPY . .

 ENTRYPOINT [ "node", "server.js" ]