FROM node:12

#create app directory
WORKDIR /movie-analyst-ui
#Install app dependencies

COPY . .
#COPY package*.json ./
EXPOSE 3030
ENV BACKEND_URL=backend:3000
RUN npm install 


#COPY . .

#CMD ["npm", "start"]
CMD [ "node", "/movie-analyst-ui/server.js" ]
