FROM node:latest

# Create app directory
RUN mkdir -p /usr/src/app/server
WORKDIR /usr/src/app/server

COPY package.json /usr/src/app/server
RUN npm install

COPY . /usr/src/app/server

EXPOSE 8080

CMD [ "npm", "start" ]
