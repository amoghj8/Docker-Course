FROM node:alpine

WORKDIR /Users/amogh/Desktop/simpleweb

COPY ./package.json ./

RUN npm install

COPY ./ ./

CMD ["npm", "start"]