# base image
FROM node:20-alpine

# working directory
WORKDIR /app

# copy package json file
COPY package.json .

# install dependencies
RUN npm install

#copy files
COPY . .

# backend running port
EXPOSE 3000

# start the app
CMD [ "npm" , "start"]