FROM node:19-alpine

EXPOSE 8000

WORKDIR /server

COPY . /server

RUN npm install

CMD ["npm", "run", "start"]