 FROM node:latest

 RUN mkdir -p /app
 WORKDIR /app
 #/usr/src/app
 COPY package.json /app
 RUN npm install

 COPY . /app

 EXPOSE 7500

 CMD ["npm", "start"]
