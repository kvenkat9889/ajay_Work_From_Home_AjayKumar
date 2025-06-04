FROM node:18

WORKDIR /app

COPY server.js ./
COPY server.env ./
COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3010

CMD ["node", "server.js"]

