FROM node:18-alpine3.15

WORKDIR /app

COPY package.json /app/package.json

RUN yarn install

COPY . .

CMD ["yarn", "run", "start"]
