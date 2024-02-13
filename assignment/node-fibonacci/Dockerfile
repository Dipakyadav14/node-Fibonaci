FROM node:10-alpine

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install package-lock.json

COPY . .

EXPOSE 80

CMD [ "npm", "start" ]