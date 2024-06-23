FROM node:18-alpine

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install -g @angular/cli@latest

RUN npm install

COPY . .

EXPOSE 80

CMD ["npm", "start"]