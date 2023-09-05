FROM node:lts-alpine

WORKDIR /sneaker-city

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "run", "start"]