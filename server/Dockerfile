FROM node:lts-alpine
RUN npm install -g json-server
COPY . .
EXPOSE 80
CMD [ "json-server", "-H", "0.0.0.0", "db.json" ]
