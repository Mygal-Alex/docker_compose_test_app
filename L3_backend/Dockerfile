# syntax=docker/dockerfile:1

FROM node:18.16.0-alpine AS prod
WORKDIR app 
COPY . .
RUN npm install
EXPOSE 5000 
CMD node index.js --p 5000 --cp 3000