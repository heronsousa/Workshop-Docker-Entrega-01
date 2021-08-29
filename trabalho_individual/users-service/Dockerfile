FROM node:14

WORKDIR /app

COPY package.json yarn.lock ./

RUN yarn install

EXPOSE 7101

CMD yarn watch