FROM node:7

ARG NODE_ENV
ENV NODE_ENV $NODE_ENV
WORKDIR /usr/src/app
COPY ./app /usr/src/app
RUN npm install && npm cache clean

CMD [ "npm", "start" ]
