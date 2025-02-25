# use the base image
FROM node:20-alpine

# set directory
WORKDIR /app

# copy package & package-lock json files
COPY package*.json ./

# install dependencies
RUN npm install

# copy files
COPY . .

# backend running port
EXPOSE 4000

# start application
CMD [ "npx", "nodemon", "server.js" ]