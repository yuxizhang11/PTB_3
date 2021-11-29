FROM node:14.17.0-alpine3.13
WORKDIR /app

#RUN npm install @reduxjs/toolkit -- nicht nötig
COPY package.json .
RUN npm install
COPY . .
CMD ["npm","start"]