FROM node:18.6 AS build

WORKDIR /app

COPY . /app

RUN npm install

RUN npm i -g serve

RUN npm run build

EXPOSE 5000

CMD ["serve", "-s", "dist", "-p", "5000"]
