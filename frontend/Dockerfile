FROM node:16-alpine 

WORKDIR /frontend

COPY . .

RUN npm install -g npm@8.19.3

RUN npm run build
