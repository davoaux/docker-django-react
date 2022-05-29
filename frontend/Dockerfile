FROM node:18-alpine3.14

WORKDIR /frontend

ENV PATH /frontend/node_modules/.bin:$PATH

COPY package.json ./
COPY package-lock.json ./

RUN npm install
RUN npm install react-scripts@latest

COPY . ./