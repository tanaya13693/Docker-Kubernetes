
#Use an existing docker image as base
FROM node:alpine

#Install dependencies
COPY ./ ./
RUN npm install

#Default command
CMD ["npm", "start"]