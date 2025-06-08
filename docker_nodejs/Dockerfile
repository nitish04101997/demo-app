FROM node:14-alpine
WORKDIR /app
COPY . /app
RUN npm install
ENV NAME docker-nodejs
EXPOSE 3000
CMD [ "npm" , "start"]
 
