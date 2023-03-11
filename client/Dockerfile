FROM node:lts

WORKDIR /teebay/client
COPY package*.json ./

RUN npm install

COPY . ./

CMD ["npm", "start"]
