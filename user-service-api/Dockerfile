FROM node:15.8.0-alpine
WORKDIR /app
ADD package*.json ./
RUN npm install
ADD . .
CMD node index.js