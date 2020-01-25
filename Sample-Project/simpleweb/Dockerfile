
#Use an existing docker image as base
FROM node:alpine

WORKDIR /usr/app

#Install dependencies
COPY ./ ./
RUN npm install

#Default command
CMD ["npm", "start"]