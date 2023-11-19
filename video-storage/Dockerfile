FROM node:21.1.0-alpine              
WORKDIR /Users/piyushpurohit/Documents/FlixTube/new-project-1                 
COPY package*.json ./                 
RUN npm install --only=production 
COPY ./src ./src               
CMD npm start 