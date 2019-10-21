FROM node:latest

LABEL maintainer="kob"

COPY . /app
WORKDIR /app
ENV DONUT_DBUSER hebbo
ENV DONUT_DBPWD ABC.123
ENV DONUT_DBHOST cluster0-2nqfg.mongodb.net
ENV DONUT_DBNAME test


RUN npm install

ENTRYPOINT ["npm", "start"]