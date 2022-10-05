FROM node:14

WORKDIR /node/project1

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

CMD ["node", "server.js"]