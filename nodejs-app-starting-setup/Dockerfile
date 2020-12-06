# Commands executed when building image:
FROM node:14
WORKDIR /app
COPY package.json .
RUN npm install
COPY . .
# expose port 3000 (because used by express in server.js)
EXPOSE 3000

# CMD executes when the container is started:
CMD [ "node", "server.js" ]