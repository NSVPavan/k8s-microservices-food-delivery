FROM node:14-buster

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3003

CMD ["node", "app.js"]
