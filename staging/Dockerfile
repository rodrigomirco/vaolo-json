FROM node:latest

RUN npm install json-server --save-dev

WORKDIR /data
VOLUME /data

EXPOSE 80
ADD server.js /server.js
ENTRYPOINT ["node", "/server.js"]
CMD []
