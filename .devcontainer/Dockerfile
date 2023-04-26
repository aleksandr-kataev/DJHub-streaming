FROM node:18-alpine
RUN apk --no-cache add git openssh

WORKDIR /streaming-src

COPY . .

RUN npm install

EXPOSE 3002