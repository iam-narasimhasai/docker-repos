FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ENV PORT 1200

EXPOSE 3000

CMD [ "npm", "start" ]