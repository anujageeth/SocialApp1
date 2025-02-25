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

# start the app
CMD [ "npm" , "start"]