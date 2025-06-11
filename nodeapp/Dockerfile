FROM node:24.2

ENV MONGO_DB_USERNAME=harsh \
  MONGO_DB_PASSWORD=harsh

RUN mkdir -p nodeapp
RUN npm i -g nodemon

COPY . /nodeapp

CMD ["nodemon","/nodeapp/index.js"]