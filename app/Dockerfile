FROM ubuntu:latest
LABEL authors="sahilmane"
FROM node:18

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3000

CMD ["node", "server.js"]
ENTRYPOINT ["top", "-b"]