FROM node:lts-alpine3.11

WORKDIR /src

COPY package*.json ./

RUN npm install

COPY . .

CMD ["node", "app.js"]