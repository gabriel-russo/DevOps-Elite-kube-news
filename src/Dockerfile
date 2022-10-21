FROM node:18.11.0-alpine

WORKDIR /app

COPY package* ./

RUN npm install

COPY . .

EXPOSE 8080

CMD ["node", "server.js"]
