
FROM node 
WORK DIR /app
COPY package*.json ./
RURN npm install
COPY . .
EXPOSE 8080
CMD ['node', "server.js"]
