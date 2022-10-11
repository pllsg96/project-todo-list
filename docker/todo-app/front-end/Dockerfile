FROM node:14-alpine

WORKDIR /app

ADD node_modules.tar.gz ./

COPY ./src ./src

EXPOSE 3001

CMD ["npm", "start"]