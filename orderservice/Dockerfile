FROM node:latest-alpine

LABEL author="komalsingh54@gmail.com"

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install --only=production

COPY . ./

CMD ["npm", "start"]