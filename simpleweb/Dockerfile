# Specify base image
FROM node:alpine
WORKDIR /usr/app
# Install some depenendencies
COPY ./package.json ./
RUN npm install
COPY ./ ./
# default Command
CMD ["npm", "start"]