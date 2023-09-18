FROM node:14-bullseye

WORKDIR /usr/src/app

COPY . /usr/src/app

RUN npm --prefix ./client --production install && npm --prefix ./server --production install 

EXPOSE 3000

CMD ["npm start"]