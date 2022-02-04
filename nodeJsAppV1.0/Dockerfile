# specify a base image
FROM node:alpine

# specify a working directory
WORKDIR /usr/app

# copy build files
COPY ./package.json ./

# install dependencies
RUN npm install

# copy full directory
COPY ./ ./

# run a command
CMD ["npm", "start"]
