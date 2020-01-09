FROM node:alpine

WORKDIR /home/node
COPY ./package.json ./package.json
RUN npm install

COPY ./index.js ./index.js

CMD ["npm", "start"]