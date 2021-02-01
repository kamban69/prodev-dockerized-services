FROM node:15
WORKDIR /usr/src/authapp-v2

COPY package*.json ./
RUN npm install

COPY . .
EXPOSE 80
CMD ["node","server.mjs"]