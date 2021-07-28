# set the base image
FROM node:alpine

# set the working directory
WORKDIR '/app'

# install dependencies
COPY . .
RUN npm install express
RUN npm install express-session

# expose the port
EXPOSE 8080

# default commands
CMD ["npm", "start"]
