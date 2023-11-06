FROM node:20

WORKDIR /usr/src/app/client

COPY client/package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm","run","dev"]