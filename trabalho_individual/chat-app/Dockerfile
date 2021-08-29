FROM node:14

WORKDIR /app

COPY package.json yarn.lock ./

RUN yarn install

EXPOSE 7001

CMD yarn watch