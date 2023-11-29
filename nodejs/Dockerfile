ARG TAG=latest
ARG PORT=8080
FROM node:${TAG}
WORKDIR /home/node/app
COPY package*.json ./
RUN npm install
COPY . .
CMD [ "npm", "run", "start" ]
EXPOSE ${PORT}