FROM node:18.14.0-alpine

WORKDIR /frontend

EXPOSE 3000

COPY package*.json .

RUN npm i

COPY . .
