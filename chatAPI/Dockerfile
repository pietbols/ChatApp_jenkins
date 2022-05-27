FROM node

WORKDIR /home/node/app

COPY package*.json ./

RUN npm install

COPY *.js ./

ENV NODE_ENV=production

CMD [ "node", "index.js" ]

EXPOSE 3000
