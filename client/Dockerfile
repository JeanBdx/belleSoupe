FROM node:latest

# Create app directory
RUN mkdir -p /usr/src/app/client
WORKDIR /usr/src/app/client

COPY package.json /usr/src/app/client

COPY . /usr/src/app/client 
RUN  npm install
RUN yarn

EXPOSE 3000

CMD [ "npm", "start" ]
