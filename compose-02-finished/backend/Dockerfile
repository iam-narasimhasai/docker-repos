FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ENV MONGODB_USERNAME=sai
ENV MONGODB_PASSWORD=secret

CMD ["npm", "start"]