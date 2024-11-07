FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

VOLUME [ "/app/feedback" ] #this creates anonymous volume after running the container you can check docker volume ls u can see volume

EXPOSE 124

CMD [ "node", "server.js" ]