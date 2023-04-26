FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app

ADD node_modules.tar.gz ./app

COPY ./src ./app/src

EXPOSE 3001

CMD ["npm", "start"]