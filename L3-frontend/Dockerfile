# syntax=docker/dockerfile:1

FROM node:18.16.0-alpine AS prod
WORKDIR app 
COPY . .
RUN npm install
RUN npm run build
EXPOSE 3000
CMD npm start