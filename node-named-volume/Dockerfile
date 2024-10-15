FROM node:14

WORKDIR /app/feedback

COPY package.json /app/feedback

RUN npm install

COPY . /app/feedback

EXPOSE 80

CMD [ "node", "server.js" ]