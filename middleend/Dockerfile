FROM node:18

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

RUN npm install bcrypt

COPY . .

EXPOSE 3000

CMD ["node", "index.js"]