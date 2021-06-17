FROM node:16-buster

WORKDIR /app

ADD package.json package-lock.json ./
RUN npm ci

ADD . ./

CMD ["npm", "run", "start:dev"]