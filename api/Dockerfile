FROM node:18.14.0-alpine

WORKDIR /api

EXPOSE 5000

COPY package*.json .

RUN npm i

COPY . .
