FROM node:16.14-alpine

WORKDIR /frontend
RUN chown -R node:node /frontend

COPY package*.json .
RUN npm install
COPY . .
