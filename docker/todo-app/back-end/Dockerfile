FROM node:14-alpine

WORKDIR /app

ADD node_modules.tar.gz ./

COPY ./docker/todo-app/back-end/Dockerfile ./src

EXPOSE 3001

CMD ["npm", "start"]